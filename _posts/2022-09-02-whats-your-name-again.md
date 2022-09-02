---
title: "What's your name again?"
date: 2022-09-02T11:30:30-04:00
categories:
  - blog
tags:
  - NLP
  - AI
  - Android
  - Mobile
---

I got laid off recently, just before I was about to go on parental leave. Aside from the extra unpaid time off I have been able to spend with my family, I built an Android app ([free, go try it out][app-download]) that attempts to address the scenario where you forget someones name mid-conversation. The app listens for voices and attempts to parse out human names, by applying some basic heuristics, and sending you a notification so you can glance at your phone.

Check out the project:

{% include video id="???" provider="youtube" %}

This is likely illegal to use in public, and it's kind of a creepy thing to have running in your pocket. For what it's worth, [I open-sourced the project so you can see everything that's going on for yourself][github], however I explain most of the details in the video.

[github]: https://github.com/calebolson123/WhatsYourName
[app-download]: https://github.com/calebolson123/WhatsYourName/raw/main/WhatsYourName/app/release/app-release.apk