---
title: "Draw your Conversations"
date: 2022-10-14T11:30:30-04:00
categories:
  - blog
tags:
  - Stable Diffusion
  - Whisper
  - AI
  - Draw
  - Discord
  - Android
---
Stable Diffusion blew up the internet with the very impressive images it proved to be able to generate via simple text prompts. People are generating impressive handcrafted art with it, however I wanted to blur the lines between manually written text prompts, and the real world.

My idea was to transcribe voices to text, and then apply some heuristics and NLP techniques to the raw conversation in order to transform it into a colorful prompt which Stable Diffusion can draw. Using [OpenAI's newly released Whisper][whisper], I created a service which transcribes conversations to text, summarizes & enriches the text, generates an image, and returns it to the client. In the video I made an Android app and a Discord bot which both interface with the same server.

Check out the project:

{% include video id="rwcyZxLGel8" provider="youtube" %}

I [open sourced the server code for this project][project-code]. Feel free to pull it down and try it out with Postman, or any frontend you come up with as an audio source.

[project-code]: https://github.com/calebolson123/DrawYourConversations
[stable-diffusion]: https://github.com/CompVis/stable-diffusion
[whisper]: https://openai.com/blog/whisper/