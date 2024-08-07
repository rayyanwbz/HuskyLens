# HuskyLens
Explore HuskyLens AI sensor's seven built-in functions: face recognition, object tracking, object recognition, line tracking, color recognition, tag recognition, and object classification. Use Arduino to turn on an LED when HuskyLens detects a face.


---

# HuskyLens and Arduino Integration

## Introduction

This project demonstrates the integration of HuskyLens, an AI vision sensor, with an Arduino. The HuskyLens offers seven built-in functions: face recognition, object tracking, object recognition, line tracking, color recognition, tag recognition, and object classification. This README provides an overview of these functions and guides you through using the Arduino to switch ON an LED when the HuskyLens detects a face.

## Table of Contents

1. [Requirements](#requirements)
2. [Setup](#setup)
3. [HuskyLens Built-in Functions](#huskyLens-built-in-functions)
    - [Face Recognition](#face-recognition)
    - [Object Tracking](#object-tracking)
    - [Object Recognition](#object-recognition)
    - [Line Tracking](#line-tracking)
    - [Color Recognition](#color-recognition)
    - [Tag Recognition](#tag-recognition)
    - [Object Classification](#object-classification)
4. [Arduino Integration](#arduino-integration)
    - [Switching ON an LED on Face Detection](#switching-on-an-led-on-face-detection)
5. [Conclusion](#conclusion)

## Requirements

- HuskyLens AI camera
- Arduino board (e.g., Arduino Uno)
- LED
- Resistor (220Ω recommended)
- Breadboard and jumper wires
- USB cable for programming the Arduino
- HuskyLens and Arduino libraries

## Setup

1. **Connect the HuskyLens to the Arduino:**
   - VCC (HuskyLens) to 5V (Arduino)
   - GND (HuskyLens) to GND (Arduino)
   - TX (HuskyLens) to RX (Arduino)
   - RX (HuskyLens) to TX (Arduino)

2. **Connect the LED to the Arduino:**
   - Connect the anode (long leg) of the LED to a digital pin (e.g., pin 7) through a 220Ω resistor.
   - Connect the cathode (short leg) of the LED to GND.

3. **Install Libraries:**
   - Install the HuskyLens Arduino library from the Arduino Library Manager.

## HuskyLens Built-in Functions

### Face Recognition

Face recognition allows the HuskyLens to recognize and remember human faces. It can identify different faces and trigger specific actions based on the recognition.

### Object Tracking

Object tracking allows the HuskyLens to follow a specific object. It uses machine learning to keep the object in the frame and adjust its position accordingly.

### Object Recognition

Object recognition enables the HuskyLens to recognize pre-trained objects. It can identify various objects and provide their positions and labels.

### Line Tracking

Line tracking is used for following lines. This function is beneficial for creating line-following robots and can recognize different paths.

### Color Recognition

Color recognition allows the HuskyLens to detect and identify different colors. This can be used for sorting objects or triggering actions based on color.

### Tag Recognition

Tag recognition is used to identify specific tags or markers. This is useful in augmented reality applications or for triggering actions when a tag is detected.

### Object Classification

Object classification enables the HuskyLens to categorize objects into different classes. It can be trained to recognize different types of objects and sort them accordingly.

## Arduino Integration

### Switching ON an LED on Face Detection

This example demonstrates how to use the HuskyLens to switch ON an LED when a face is detected. 

1. **Connect the LED to a digital pin on the Arduino (e.g., pin 7).**
2. **Use the HuskyLens Arduino library to interface with the HuskyLens.**
3. **In the Arduino code, set up the HuskyLens to detect faces.**
4. **In the `loop` function, check for face detection and switch the LED ON or OFF based on the detection.**

## Conclusion

This project showcases the powerful capabilities of the HuskyLens AI camera and its integration with an Arduino. By leveraging the built-in functions of the HuskyLens, you can create a wide range of interactive and intelligent projects. The provided example demonstrates how to use face recognition to control an LED, illustrating the potential for further applications.


