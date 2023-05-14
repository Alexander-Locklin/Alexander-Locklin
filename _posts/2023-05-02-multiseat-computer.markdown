---
layout: post
title:  "Multiseat Computer"
date:   2023-05-02 21:50:41 -0400
categories: Computers
---

Building computers can become very costly, so being able to split a computer for two users would reduce the cost of having to buy two seperate desktops. I discovered the program [Aster](https://www.ibik.ru/) which allows a single computer to be split into multiple users.

![Multiseat Users](/assets/multiseat.jpg)

These two images show what seem to be two different computer setups, but are actually running on the one computer in the left image using the Aster program. A passthrough in the wall allows for display cables and usb to be passed through to the other room.

![Desktop Computer](/assets/desktop.jpg)

**Computer Specifications:**
AMD Ryzen 5700X CPU, 2x AMD Radeon 6650XT GPUs


The limitations of this project were that consumer graphics cards are not able to have their resources split between two users effectively. A problem occuring was that when one user was putting heavy load on the system, the GPU would not have resources allocated for the second user. This problem is primarily on the GPU, but not the CPU, so a single CPU can be used by both users. Two graphics cards can be split between two users much more effectively while using both at their full capacity. 

For lighter loads such as usage in a library, a single graphics card would be sufficient in outputing a display signal to multiple monitors, and running light tasts such as internet browsing.

![Aster](/assets/aster.jpg)

Aster allows display outputs, usb IO, and audio IO all to be allocated to a single user, or to be shared. 