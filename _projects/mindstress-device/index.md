---
layout: post
title: MINDSTRESS Device
description: The MINDSTRESS device is designed to address the growing need for affordable mental health monitoring solutions in Vietnam. Given the high prevalence of mental health issues, particularly among young individuals, this device aims to provide an accessible, cost-effective tool for detecting emotional stress and offering mindfulness practices to users.
collaborators: Nguyen Yen Nhi, Le Thi Viet Anh
skills: 
- Embedded Systems Development
- Sensor Integration & Signal Processing
- Circuit Design & Prototyping
- User Interface Design
- Audio Processing
- Product Design & Cost Optimization
- Data Analysis & Research
- Project Management & Team Collaboration
main-image: /project.jpg 
---

---
# Design Overview 

## **1. High-Level Requirements**
- **Affordability:** The device must be cost-effective for low- to middle-income individuals.
- **User-Friendly Interface:** Simple, intuitive design with a clear display.
- **Accurate Stress Detection:** Utilizes a MAX30102 pulse oximeter to assess emotional levels based on heart rate.
- **Relaxation Guidance:** Provides audio solutions such as meditation music to help users manage stress.
- **Privacy Protection:** Ensures user data remains confidential.

## **2. Technical Contributions**
**Hardware Components**
- Arduino Uno Compatible microcontroller
- MAX30102 PPG Heart Rate and Oximeter Sensor (I2C/UART)
- LCD Text Display (2004) with I2C Adapter
- Mini MP3 Player Module with SD Card support
- Mini 2W Speaker
- Breadboard MB-102 for circuit connections
- Enclosure made of mica material

## **3. Software Implementation**
- **Heart Rate Analysis Algorithm:** Converts BPM into emotional status categories (Relaxed, Normal, Good, Not Good)
- **Mindfulness Suggestion System:** Plays corresponding audio recommendations based on detected emotional levels. 
    
# Visual Representations

## **1. Electronics circuit diagram**
{% include image-gallery.html images="circuit.jpg" height="400" %} 

## **2. 3D sketch design**
{% include image-gallery.html images="1.jpg" height="300" %} 
{% include image-gallery.html images="2.jpg" height="300" %} 
{% include image-gallery.html images="3.png" height="300" %} 

## **3. User Flow**
{% include image-gallery.html images="user_flow.png" height="400" %}

## **4. Block Diagram**
{% include image-gallery.html images="block_diagram.png" height="400" %}

# Results and Evaluation

The MINDSTRESS device successfully met its initial objectives by providing a functional prototype capable of detecting emotional stress and offering relaxation solutions.
- **Accuracy:** The heart rate sensor provided reliable readings comparable to standard calibration devices.
- **Cost-effectiveness:** At an estimated production cost of 900,000-1,000,000 VND, it remains significantly cheaper than alternatives like Garmin and Apple smartwatches.
- **Usability:** User tests demonstrated ease of use, though improvements such as a countdown timer for results were identified as future enhancements.
- **Limitations:** The device is not suitable for individuals with high blood pressure or those who have recently exercised, as these factors may affect heart rate readings.

# Future Improvements
- Incorporation of additional biometric sensors for enhanced stress detection.
- Refinement of software algorithms to improve accuracy.
- Integration of wireless connectivity for data tracking.
- Enhancements to the user interface for improved accessibility.
