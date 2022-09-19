---
title: "Stable Diffusion"
date: 2022-09-20T02:44:32+06:00
draft: false
---

I have run stable diffusion on my GTX 1060.

It has only 6gb of vram. So I used [this version.](https://github.com/basujindal/stable-diffusion)

I tried to run the docker way. But the docker image became huge and it is based on ubuntu base image.

I actually stopped while building that image and found out the image was 14gb. So i took the virtual environment way. And I have tensorflow==2.9 installed. So i have to use conda to match cuda version for the required pytorch cuda version.