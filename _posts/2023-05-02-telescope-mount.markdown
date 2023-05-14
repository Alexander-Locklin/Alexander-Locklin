---
layout: post
title:  "Telescope Mount"
date:   2023-05-02 21:50:41 -0400
categories: astronomy electronics making
---

The telescope mount project is a project that I have started to improve the quality of my astrophotography images. The design of the mount is a barn door tracker.

![Barn Door Tracker](/assets/barndoortracker1.jpg)

This first design includes a CD Disk with a print marking degrees on it. As the disk is spun, the bolt attached will rise the top board allowing the tracking of the sky. One rotation per minute is nessesary for accurate tracking.

The first addition to my design was a small laser diode which helps me see exactly where to spin the disc. Continuously moving to the next marker spinning clockwise every 2.5 seconds is suitable for wide angle lenses.

![Motor Controller](/assets/steppermotorcontroller1.jpg)

This is a motor controller for a stepper-motor I plan on adding to the tracker. With a stepper-motor, I can very accurately drive the bolt at 1 RPM for as long as I need without having to worry about human error. The controller uses a Seeeduino Xiao and an SN754410 H-Bridge motor controller.



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
