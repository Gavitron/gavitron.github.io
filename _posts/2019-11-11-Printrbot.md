---
layout: post
title: Printrbot Notes
categories:  [printrbot,hardware,hacking,3dprinting,electronics, post]
tags:  [printrbot,hardware,hacking,3dprinting,electronics]
---

Looks like a lot of the printrbot info is slipping into the memory hole these days.  Here's a record of my upgrades
<!--more-->

to add an LCD and buttons to the printrboard, Rick Shear did a lot of work, but his blog is now defunct, and I had to download these from the wayback machine;

schematic
pinout png

here's some other info:

links to other things I referenced:


Notes:

  I rang out pin 9 on EXP1 header, and pins 3,4,9 on EXP2.  none of them appear to connect to anything at all, and is supported by whatever board art/schematics I could find.

  EXP1 pin 9 used to be a reset line, but for Rev F, this is no longer.  if you want to breakout a reset pin, you'll have to solder directly to the onboard tact switch.

  EXP2 pins 3,4 might have been BOOT1/BOOT2 at some time, now those are on a seperate jumper header.

  EXP9 never had a purpose, so idk what it was there for.

LCD board

  I created a new version of the LCD board, it's smaller, which is my main reason for building it, and it breaks out the controls onto headers, for simpler enclosure design.


https://upverter.com/design/gavitron/printrbord/

based off of https://web.archive.org/web/20171112065222/http://rs-micro.com/?p=317

http://www.appfruits.com/2014/11/custom-lcd-controller-for-printrbot-simple-metal/
http://electronics.onebeartoe.org/3d-printing/printers/printrbot-simple-metal/upgrades/lcd-with-rotary-button/resources/
https://venemoblog.wordpress.com/2017/04/17/20x4-lcd-display-for-printrbot-simple/
http://web.archive.org/web/20171002024955/http://rs-micro.com:80/wordpress/
http://web.archive.org/web/20160410004555/http://rs-micro.com/files/Printrbot/LCD-Adapter.pdf
https://reprap.org/wiki/Printrboard

