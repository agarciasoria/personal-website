---
title: "Track Start Simulator"
date: 2026-04-15
draft: false
description: "A mobile-first web app that uses smartphone motion sensors to simulate a track starter and calculate sprint reaction times with millisecond precision."
tags: ["react", "typescript", "tailwind", "web-audio-api", "accelerometer", "athletics", "vite"]
external_link: "https://agarciasoria.github.io/track-start-simulator/"
---

## Overview

The Track Start Simulator is a web application designed specifically for mobile devices to help sprinters practice their starting block reaction times. It mimics the exact sequence of a real track and field competition ("On your marks. Set. BANG") and leverages the smartphone's built-in motion sensors (accelerometer) to detect the precise moment the athlete explodes out of the blocks. 

## ✨ Key Features

- **High-Precision Reaction Timer:** Calculates reaction times down to the thousandth of a second using `performance.now()`. Flags sub-0.100s reactions as official false starts.
- **Motion Detection & False Starts:** Place the phone against the starting block. If movement is detected during the "SET" phase, a double-gun sound triggers indicating a false start.
- **Procedural Audio Cues:** Authentic timing with synthesized speech for the starter's commands and a zero-latency, math-generated synthetic gun sound.
- **Variable Gun Delay:** Mimics a human starter by firing the gun at a random interval within a customizable window.
- **Live Sensor Meter:** Displays raw sensor activity to help athletes calibrate the sensitivity threshold for their specific blocks and surface.

## Try it out
*(Note: Best experienced on a mobile device!)*

🚀 **[Launch Track Start Simulator](https://agarciasoria.github.io/track-start-simulator/)**