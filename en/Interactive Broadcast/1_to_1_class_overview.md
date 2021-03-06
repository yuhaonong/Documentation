
---
title: One-to-one Online Classroom
description: 
platform: All Platforms
updatedAt: Fri Feb 28 2020 08:06:53 GMT+0800 (CST)
---
# One-to-one Online Classroom
## Introduction

In a One-to-one Online Classroom scenario, an online teacher gives an exclusive lesson to only one student, and both can interact in real time. This typical one-to-one scenario can find uses in online tutoring, language lessons, music lessons, and more.

This article describes how to use the Agora SDKs to implement a One-to-one Online Classroom scenario.

![](https://web-cdn.agora.io/docs-files/1582860769190)

## Feature list

You can use the Agora SDKs to implement the following features for your project.

| Feature | Description | 
| ---------------- | ---------------- | 
| Real-time communication     | The student attends the teacher's online class. During the class, both can see and talk to each other in real time, creating a positive interaction.      | 
| Real-time messaging | Both the teacher and the student can chat with each other through text messages. |
| Whiteboard | The teacher can share a Powerpoint slide, a Word or PDF file, or even an audio or video file on it.<br>The teacher and the student can also write things collaboratively on the whiteboard.   |
| Recording | The teacher can record the class and share the recording through a link for future review or evaluation. |
| Class management | The teacher starts or ends the class, and manages the student's privilege for sending audio, video, or real-time messages. |
| Device and network test | Before the class, the teacher can test whether the microphone and camera are working properly. <br> During the class, both the teacher and the student can monitor the network quality in real time. |
| Screen share | The teacher can share the screen with the student.|


## Try the demo

Agora provides the One-to-one Online Classroom demos on the following platforms. 

| Android | iOS | PC Web | Windows | macOS |
| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| [Download](https://www.pgyer.com/agora_edu) (Password: 123)  | ![](https://web-cdn.agora.io/docs-files/1581407452682) |  [Try it out](https://solutions.agora.io/education/web/#/)      | Coming up soon | Coming up soon |

In which:
- The client for the student can be Android, iOS, or Web for now.
- The client for the teacher is Web for now.

Follow these steps to try the demo:
1. Fill in the classroom number and username.
2. Choose **One-to-One**.
3. Set your role as either **Teacher** or **Student**.
4. Click **Join** to enter the classroom.

## Technical solutions

Agora recommends using the following SDKs or services to implement a One-to-one Online Classroom scenario.

![](https://web-cdn.agora.io/docs-files/1582862848646)

| SDK | Function | 
| ---------------- | ---------------- | 
| Agora RTC SDK      | Joins an RTC channel for real-time audio and video communication.      | 
| Agora RTM SDK      | Logs in the RTM system and joins an RTM channel for managing the channel, and sending and receiving text messages.      | 
| Agora Cloud Recording | Records the class in real time and replays it immediately after the recording completes. |
| The whiteboard SDK (third-party) | Uses the whiteboard for writing or file sharing. |

## Advantages

This technical solution has the following advantages:

**Low latency**

Agora SD-RTN<sup>TM</sup> is Agora's proprietary network for audio and video transmission,  covering more than 200 countries and regions. The intelligent routing algorithms it uses ensure that the average end-to-end latency worldwide is less than 300 ms.

**High service stability and accessibility**

Agora's services are in accordance with SLA (Service-Level Agreement), ensuring an over 99% login success rate and 99.99% service accessibility throughout the year.

**Resilience to packet loss**

Agora's anti-packet-loss algorithm ensures a smooth audio and video experience when the packet loss rate reaches 60% or a smooth audio experience when the rate hits 70%, minimizing the freeze rate and dropped calls.


**High audio quality**

The following technologies ensure that the speaker's voice always stands out from a noisy environment:
- A maximum audio sampling rate of 48 kHz for full band frequency.
- The 3A algorithm featuring automatic echo cancellation (AEC), automatic noise suppression (ANS), and automatic gain control (AGC).
- The AI noise reduction algorithm.

**High-definition video**

Agora optimizes the video experience from the following perspectives:
- Supports a maximum resolution of 4K to accommodate the growing demand for high-definition video. 
- Works with most main-stream devices, platforms, and scenarios by supporting H.265 codec, super resolution, and perceptual video. 
- Uses a dynamic bitrate algorithm to adapt the video bitrate to the real-time network conditions for resolutions from 48p to 1080p.
- For a set resolution and frame rate, consumes less bandwidth and renders higher quality video.



**Extra functions**

You can also add the following components or services to your project:

- Whiteboard: You can add a whiteboard to an online classroom, which can be used to write things down, share a Powerpoint slide, and share the H5 animation courseware.
- Screen share: Agora supports the teacher sharing the screen, courseware materials, and notes with the student.
- Recording: You can even embed recording in your class with our on-premise recording or cloud recording service.

**Traceability**

- Agora provides a variety of methods for measuring the network quality and testing the device before the class. We also have callbacks that report on communication quality during the class. Use these methods to ensure smooth classroom experience and for troubleshooting.
- You can also use [Agora Analytics](https://console.agora.io/analytics/call/search) to monitor the quality, user behavior, device state, and Quality of Experience (QoE)/Quality of Service (QoS) statistics. 

**Compatibility**

Our SDKs are compatible with more than 6000 devices, covering over 18 platforms and development architectures, including Windows, macOS, Web, iOS, Android, and Electron. This ensures that the teacher and the student share the same experience.
