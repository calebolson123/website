---
title: "Dog Poop Detector"
date: 2022-01-14T11:30:30-04:00
categories:
  - blog
tags:
  - Dog
  - Poop
  - AI
  - Computer vision
---
No one likes dealing with dog poop, and I'm lazy, so I let me dog outside and forget about it. Then over time I have a mine field in my backyard. Over this past winter break, I had the idea to leverage my security camera as a means to detect if my dog is poops, and then store off the location. After a couple of weeks head down, I emerged with what I believe is the first dog poop detector using only video (livestream).

Check out the project:

{% include video id="uWZu3rnj-kQ" provider="youtube" %}

I [open sourced the code for this project][project-code]. Feel free to pull it down and try to configure it with your own security camera. Aside from configuration with your camera, the main part which is semi biased to my setup, is the computer vision model. If you're serious about setting this up, read up on [DeepLabCut][deep-lab-cut] and train your own model with images of your own dog. I had aspirations to train a model which worked for many dog breeds, however I got distracted with other projects!

Feel free to reach out if you have any questions and I'll try to help where I can.

[project-code]: https://github.com/calebolson123/DogPoopDetector
[deep-lab-cut]: https://github.com/DeepLabCut/DeepLabCut