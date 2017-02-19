---
layout: post
title: Reversing Archives
author: Hunter Stanton
---

# Reversing Archives
Reversing archive formats is always tricky. Currently, I'm working on an unpacker for files used by the GameCube/PS2/Wii game "The Grim Adventures of Billy and Mandy" which is based on the TV show with the same name. It's a format called JAM, presumably an inhouse format created by the developer, High Voltage Software.

At first glance, it's pretty simple - static offsets for mostly everything, null terminated fixed maximum length strings (either 4 bytes or 8 bytes), no encryption or compression, counts easily accessible for the number of files inside the archive, etc. However, there are a few troubling issues with the way the format stores its file table that I just can't figure out.

For certain JAMs, its very simplistic -  int16 file name index lookup, int16 file type index lookup, and then int32 offset. Other JAMs, though, throw this right out the window, and do things way differently. Once I figure this crucial bit out, I will be able to easily and quickly finish up my unpacker.

Hopefully soon I can crack this and then finally get a v1.0 release of the unpacker out there. Maybe someone will find it useful, but the game is fairly obscure and wasn't particularly well received, so I doubt there is anyone out there who wants to modify or examine the internals. Guess we'll see!