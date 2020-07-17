---
template: blog-post
title: "Smart Van with a Raspberry Pi 4: Part 2 GPS"
slug: /smart-van-raspbery-pi-4-part-2
date: 2020-07-17 10:05
description: "Smart Van with a Raspberry Pi 4: Part 2 GPS"
---
* sudo apt-get install gpsd
* Check which device it is, in mycase  dev/ttyACM0
* Add GPSD_OPTIONS="/dev/ttyACM0" and GPSD_SOCKET="/var/run/gpsd.sock" to **/etc/default/gpsd**

sudo apt-get install gpsd