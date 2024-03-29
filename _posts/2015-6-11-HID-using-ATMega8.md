---
layout: post
title: Human computer interaction - Accelrometer(MPU-6050), VUSB, ATMega8
subtitle: >-
  a simple hand held poinitng device using virutal usb stack and ATMega8
tags:
  - electronics
  - hid
  - pointing device
  - atmega8
  - atmel
  - vusb
categories:
  - electronics
author: Akash Gutha
header_img: img/main-bg.jpg
published: true
automated_prototype_video_id: VrKFSRQjys4
wireless_video_id: t9G43n3Bgvw
wired_video_id: 9c5HWRjiruo
---
__What is HID?__
HID stands for `Human interface device`. Any device that a human uses to interact with a computer can come under this category of human interface devices. You might be knowing these by other names such as `Human machine interfaces`. More advanced implementations include `Brain machine interfaces`. 

__What is this project about?__
This project is about creating an interaction device, that a person can use to interact with the computer. In this project we specifically used an accelerometer capture data from hand movement and translate it into Mouse movement.

One of the first experiments that i did with HID is to setup automated mouse movement

{% include youtubevideo.html id=page.automated_prototype_video_id %}


The __Wired__ version takes input from the IMU (Inertial Motion Unit MPU 6050) and passes the information to the micro-controller which then process the information and sends instructions to the computer to move the cursor/pointer.

{% include youtubevideo.html id=page.wired_video_id %}

The __wireless HID__
{% include youtubevideo.html id=page.wireless_video_id %}

The paper we wrote for this device needed some major rewrites and hence we decided not to publish it. After college it was hard for everyone to find time to invest in the paper as everyone got busy with their lives.

<iframe class="resume" src="https://drive.google.com/file/d/0B5LD46uw6OKIX1o5QmpUcUZkMTVDUVI5elpJbXZWS0hKYUt3/preview" width="640" height="720"></iframe>
