# Gesture Calculator 😎🤙

Welcome to the **Gesture Calculator** – a badass project that uses computer vision and gesture recognition to crunch numbers in real time. Whether you're just chilling or deep in code, this project is your ticket to a futuristic, hands-on calculation experience.

## Overview

This project leverages [MediaPipe](https://mediapipe.dev/) and [OpenCV](https://opencv.org/) to track your hand gestures and map them to arithmetic operations. No more boring keyboards—just show your moves and let the calculator do its magic.

## Features

- **Slick Gesture Recognition:**
  - Detects all 5 fingers (yeah, even the thumb!)
  - Maps gestures like:
    - **Thumbs Up** → Addition (`+`)
    - **Thumbs Down** → Subtraction (`-`)
    - **Open Hand** → Multiplication (`*`)
    - **Rock Sign** → Division (`/`)
- **Smooth Confirmation:**
  - Uses a *Peace Sign* with a built-in delay to confirm your input so you don’t accidentally lock in the wrong number.
- **Responsive Display:**
  - The camera feed dynamically resizes with your window – keeping everything crisp and on point.
- **Real-Time Calculations:**
  - Enter numbers and operators with simple gestures and watch your math happen instantly.

## How It Works

1. **Hand Detection:**  
   MediaPipe tracks your hand and identifies key landmarks.

2. **Gesture Mapping:**  
   Each gesture is linked to a number or operation. Raise your fingers for numbers, flash a thumbs for operators.

3. **Input Confirmation:**  
   Hold up a *Peace Sign* for a sec to lock in your choice – no accidental inputs here!

4. **Calculation & Display:**  
   Once everything’s set, the calculator does its thing and displays the result in real time.

## Setup & Installation

### Prerequisites

Make sure you have Python 3.x installed along with these libraries:

- OpenCV
- MediaPipe
- NumPy

Install them via pip:

```bash
pip install opencv-python mediapipe numpy
