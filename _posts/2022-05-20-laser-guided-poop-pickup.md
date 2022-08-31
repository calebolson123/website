---
title: "Laser Guided Dog Poop Pickup System"
date: 2022-05-20T11:30:30-04:00
categories:
  - blog
tags:
  - Dog
  - Poop
  - AI
  - Computer vision
  - laser
---

This project originated from a comment on Reddit suggesting to take the [Dog Poop Detector][dog-poop-detector] a step further, now that the locations of poops are tracked over time. The idea is to route the user of the system through all the known poop locations, using the optimal path, resulting in the least steps taken. So I took a stab at it and this is what resulted:

{% include video id="rVzwHwN4-V0" provider="youtube" %}

I didn't bother open sourcing this one, as the code is very hardcoded and specific to the robo-arm I purchased, and my Raspberry Pi. Speaking of Raspberry Pi, they noticed this project and wrote about it [on their blog as well][raspberry-pi-blog]. It also made its way into [Gizmodo][gizmodo]. Pretty awesome.

[dog-poop-detector]: https://calebolson.com/blog/2022/01/14/dog-poop-detector.html
[raspberry-pi-blog]: https://www.raspberrypi.com/news/laser-guided-dog-poop-spotter/
[gizmodo]: https://gizmodo.com/dog-tech-smart-robot-laser-arm-poop-maker-security-came-1848974458