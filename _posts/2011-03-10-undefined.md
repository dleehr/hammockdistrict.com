---
layout: post
date: 2011-03-10 15:25:44
author: Dan Leehr
title: Filer and Filer Lite Updates
---

About a week ago I was contacted by someone on Apple's Developer Relations Team, regarding Filer Lite. &nbsp;Their concern was that a 3rd-party library (the FTP Server) had a vulnerability, and that without action, they may approve the app from the store. &nbsp;I needed to either address the vulnerability or remove the feature.

There is a newer version of this library available but I do not know if it addresses the vulnerability or not. &nbsp;So for my immediate response, I removed the feature. &nbsp;I&nbsp;submitted a 2.1.1 update for Filer Lite (and Filer, too). Both updates are currently in review, and yesterday Apple removed Filer Lite 2.1.0 from the store. &nbsp;I hope that 2.1.1 is approved shortly and back in the App Store.

Removing a feature was not my preferred course of action. &nbsp;I believe in focusing on great functionality and supporting the features implemented to provide that functionality. &nbsp;I was unable to support a feature that I had promised to, and I apologize to my customers for that.

The FTP server functionality has always been a source of usability issues with the apps. &nbsp;This implementation always requires additional 3rd-party software - The Finder in Mac OS X cannot upload to FTP sites, and the FTP client in Windows just doesn't work well with this particular FTP implementation. &nbsp;There were timeouts, crashes, inconsistencies, etc.

Since FTP Sharing was never a first-class experience in Filer, I've continued to improve the other functions that get files in and out. &nbsp;I've added support for iTunes USB Sharing (far faster and more reliable than the network), Tap-And-Hold, and improvements to the Web Sharing. &nbsp;These all have made it easier to get files moved around, and I will continue to develop them. &nbsp;These have all been free updates to the product.

I also plan to address any void left by removing the FTP server. &nbsp;I don't have any announcements to make today, but that upgrade will surely be free, just as the others have been.
