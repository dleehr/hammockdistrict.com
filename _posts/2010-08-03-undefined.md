---
layout: post
date: 2010-08-03 14:39:30
author: Dan Leehr
title: Filer at GSMArena Blog
---

Yesterday the blog at GSMArena [posted](http://blog.gsmarena.com/want-some-usb-file-transfers-functionality-on-your-ios-4-device-look-again-its-right-there/#more-5812) an interesting article about Filer.&nbsp; It's a good writeup, particularly this part:

> it&rsquo;s just an awesome app that deserves a pat on the back...

Seriously, though it's a good profile, and I appreciate the review.&nbsp; Interestingly, there's a definite focus on the iTunes USB sharing features of iOS 4 (that were introduced in 3.2 on iPad):

> Yeap, the most interesting thing about it is the so-called iTunes USB sharing &ndash; a new feature, which has obviously been introduced by iOS 4 and the latest iTunes.

I'm not going to argue whether or not that's the most interesting thing.&nbsp; Certainly when this feature was revealed in the iPad SDK, I knew [exactly where it would fit](/home/2010/1/27/new-sdk-requests-possibly-fulfilled.html) .&nbsp; However, I'm sure plenty of other developers did too.&nbsp; Prior to this, the only way to get files onto an iDevice was through WiFi networking, USB hacks that impersonated a digital camera, or jailbreaking.&nbsp; WiFi was the slowest and least reliable, the USB hacks were quickly banned from the App Store, and jailbreaking is a cat-and-mouse game.

As a long-time Windows Mobile / Pocket PC user, there was a common filesystem and there were definitely ways to throw files on your device and use them later.&nbsp; Not brilliant or simple ways to do it, but it could be done.&nbsp; When I started developing Filer (Downloader), the point wasn't to make something that downloaded files, it was to have a place to put stuff that didn't fit into the iTunes tethered ecosystem.&nbsp; A year ago, the network was the only legitimate way to do this, so that's where I started.&nbsp; Get a URL, download it, done.&nbsp; Need to get it out, download it the other way.

iTunes USB sharing makes getting files in and out fast, reliable, and easy.&nbsp; At first glance, it marginalizes apps like Filer.&nbsp; But in the last year, I've updated the app to focus more on doing things with your files once you've got them (Manage, Zip/RAR, Dropbox, save to photos, etc), and there was a definite shift, hence the name change.

Now, getting files onto the device is not something I have worry about as much, and I can focus on making the rest of the app better.&nbsp; As I continue to develop Filer, there will be&nbsp; more competition on innovation and usability and distinguishing features. USB Sharing is an OS feature, not an application.

Beyond the obvious applications in file managers, USB sharing enables another class of apps that just wouldn't be feasible.&nbsp; My next app will use this feature heavily, but it's not a file manager.&nbsp; It just operates on big files that aren't very WiFi-friendly.

So thanks to [GSMArena](http://blog.gsmarena.com/) for the post, I think they nailed the idea behind [Filer](/filer/).&nbsp; But knowing what users want is tricky.&nbsp; I think Apple also made a good decision here.&nbsp; There's no spiderweb of files or registry hiding away on your phone, and you can blow away an app and all its files in about 5 seconds.
