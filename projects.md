---
layout: page
title: Projects
permalink: /projects/
---

# [Nexus Heights](http://nexusheights.org) 
The apps I have made and released under my own company, Nexus Heights.

***

## Live on the App Store
<img src="{{ site.baseurl }}/images/image_resizifier_logo.png" alt="Image Resizifier Logo" />
### [Image Resizifier](http://appstor.io/go/appstore/1180432045)
A MacOS application that allows easy resizing of image assets for use in Apple's Xcode.

I developed this because I had a specific need for it, and I didn't want/find any other applications out there that had the features and simplistic GUI that I wanted.

<img src="{{ site.baseurl }}/images/rng_master_logo.jpg" alt="RNG Master Logo" style="border-radius: 50px;"/>
### [RNG Master](http://appstor.io/go/appstore/1089485378) / [RNG Master TV](http://appstor.io/go/appstore/1098269613)
A set of random number generator apps for iOS, Apple Watch, and Apple TV that supports rolling dice, generating random numbers, and flipping a coin.

I developed this in a single afternoon because I just wanted something to work on one day. Was the first application Nexus Heights ever released onto the App Store, so it was a big learning experience.

<img src="{{ site.baseurl }}/images/convert_master_logo.jpg" alt="Convert Master Logo" style="border-radius: 50px;"/>
### [Convert Master](http://appstor.io/go/appstore/1137413166)
An iOS application for converting numbers between hex, decimal, octal, and binary. Supports converting from one type, to any other type.

I made this simply because I wanted to have something on the go that could do this. It's rare that I have a need to convert numbers when out and about, but when I do, this comes in handy.

***

## Open-source

### [Ping Master](https://github.com/NexusHeights/Ping-Master)
A network pinging app for iOS. I developed this and released the source under the Nexus Heights name, because I didn't really want to release it on the App Store. Apple had recently implemented an IPv6 support requirement, so adding IPv6 support would be quite a lot of work for something so minor.

***

# Personal
Things I made in my spare time, separate from Nexus Heights.

***

## Open-source

### [COD Save Manipulator](http://github.com/HunterStanton/COD-Save-Manipulator)
A tool that is capable of manipulating savegame.svg files for the popular *Call of Duty* series. It automatically determines which game the savegame is from, which platform it is on, and which endian it is in. It can also determine if the save is an Xbox 360 STFS package or not.

It's main functions are recalculating the checksum stored in savegames, and printing information about them. I hope to expand the functionality to include enumerating saved entities, modifying health/ammunition, and more.

### [ContainerReader](http://github.com/HunterStanton/ContainerReader)
A tool that is capable of editing information about UWP (Universal Windows Program) Containers.index files. Mostly used in games, this file format is used to store information about the savegames. Mainly just filename, GUID, and package family name/PFN.

Without using this tool, finding the real names of savegames requires a hex editor. This solves that problem.

### [Currency Converter](https://github.com/HunterStanton/Currency-Converter)
This is an Apple TV app that converts currencies using live data from the Fixer.io API. I developed this for the fun of it, and because I knew it would be simple to get going. The API that powers it is very simple (one call for each conversion), so it didn't take long to make at all.

### [Song Title Generator](https://github.com/HunterStanton/Song-Title-Generator) / [Song Title Generator TV](https://github.com/HunterStanton/Song-Title-Generator-TV) / [Song Title Generator Mac](https://github.com/HunterStanton/Song-Title-Generator-Mac)
This is a set of Apple Watch/Apple TV/Macintosh apps for making song titles. It is very simple, and was developed in a single afternoon. Uses two dictionaries with an adjective-noun format, and just pulls one element from each dictionary and combines them to make a song title.

### [IW-Checksum-Fixer](https://github.com/HunterStanton/IW-Checksum-Fixer) / [Ghosts-Checksum-Fixer](https://github.com/HunterStanton/Ghosts-Checksum-Fixer) / [MWX-Checksum-Fixer](https://github.com/HunterStanton/MWX-Checksum-Fixer)
This is a set of C# applications that recalculate the checksum in Call of Duty: Ghosts, Call of Duty: Infinite Warfare, Call of Duty: Modern Warfare 2, and Call of Duty: Modern Warfare 3 savegame.svg files.

Please do not use these anymore. My other project, COD Save Manipulator, which is linked above, does this and more in just one single application. These were made before that project, and I put them here for completeness.

### [Stack Test](https://github.com/HunterStanton/Stack-Test)
This was a simple iOS app that was to help me understand the LIFO stack in the context of Swift. 

Not much use to be found here, but it was useful to me. I put it up incase someone else found it useful.

### [Splash Screen Test](https://github.com/HunterStanton/SplashScreenTest)
I challenged myself to make a splash screen in an iOS app with nothing but a timer, two views, and a segue.

This was the end-result of that challenge.
