---
layout: page
title: Getting Started
---


## What is Multi Camera Simulator?

Multi Camera Simulator (MSS) is a free simulation software tool based on Unity helping Computer Vision researchers to test and to design proof-of-concepts Vision algorithms. It can be an alternative to traditional datasets (video, PTZ cameras) specially in scenarios where we have not information or can not easily replicate in the real word.  

What can you do with MSS?

* Simulate or load any 3D scenario including animated models (pedestrians, cars...)
* Generate independient streams from multiple cameras syncronizhed
* Customize cameras in real-time (fps, location, resolution, FOV...)
* Add Artificial Intelligence to 3D models or create custom events
* Repeat an interest situation as many times as you need


## How it works

Do you have experience with OpenCV? Then, you will understand our application quickly. Let´s see an example. We are working on a people detection algorithm. 

## Schema

MSS has a Client-Server architecture. All comunications between your application and the simulator are done via a TCP connection. Thanks to this desing, there are no requirements of platform or programming language. It also allows to run it in a distributed architecture, making possible to use it by several users at the same time. 

![_config.yml]({{ site.baseurl }}/images/mss1.png)
## What technology is used

* MSS is an extension of Unity, a popular game engine with compatibility with modern API graphics (DirectX 12, Vulkan) and support for Virtual Reality (VR) devices.
* Developed in C# and using the .Net framework
* EmguCV, a .Net wrapper to the OpenCV library used for image processing.
* The open source Libjpeg-turbo image codec for the best image encoding performance possible.

## Quick start guide

Interested? Check our quick start guide.

