---
layout: post
title: MINDSTRESS Device
description:  The MINDSTRESS device is designed to address the growing need for accessible mental health monitoring in Vietnam. With over 14 million Vietnamese requiring mental health services and limited affordable solutions, this project aims to develop an inexpensive, community-friendly device. The device detects a user's emotional status through heart rate monitoring and provides mindfulness-based relaxation techniques to improve well-being.
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

**1. High-Level Requirements**
- **Affordability:** The device must be cost-effective for low- to middle-income individuals.
- **User-Friendly Interface:** Simple, intuitive design with a clear display.
- **Accurate Stress Detection:** Utilizes a MAX30102 pulse oximeter to assess emotional levels based on heart rate.
- **Relaxation Guidance:** Provides audio solutions such as meditation music to help users manage stress.
- **Privacy Protection:** Ensures user data remains confidential.

**2. Technical Contributions**
**Hardware Components**
- Arduino Uno Compatible microcontroller
- MAX30102 PPG Heart Rate and Oximeter Sensor (I2C/UART)
- LCD Text Display (2004) with I2C Adapter
- Mini MP3 Player Module with SD Card support
- Mini 2W Speaker
- Breadboard MB-102 for circuit connections
- Enclosure made of mica material

**3. Software Implementation**
- **Heart Rate Analysis Algorithm:** Converts BPM into emotional status categories (Relaxed, Normal, Good, Not Good)
- **Mindfulness Suggestion System:** Plays corresponding audio recommendations based on detected emotional levels.

**4. User Flow**
{% include image-gallery.html images="user_flow.png" height="400" %} 
    
## Visual Representations

**1. Circuit of the product**
{% include image-gallery.html images="circuit.jpg" height="400" %} 

**2. 3D sketch design**
{% include image-gallery.html images="1.jpg" height="300" %} 
{% include image-gallery.html images="2.jpg" height="300" %} 
{% include image-gallery.html images="3.png" height="300" %} 

#### Results and Evaluation

**1. Prototype Testing**
- Conducted tests with users to validate accuracy and effectiveness.
- Verified that the heart rate sensor aligns with medical-grade measurements.
  
**2. Affordability**
- Total material cost: 1,000,000 VND (~$40 USD)
- Compared to alternatives (e.g., Apple Watch, Garmin) costing over 6,000,000 VND (~$240 USD), this device is significantly more accessible.
  
**3. Community Application**
- Designed for placement in medical centers and health stations to serve multiple users.
- Potential reach: 1.02 million units per year across Vietnam.
  
**4. Limitations and Future Improvements**
- Accuracy Constraints: Users with high blood pressure or recent physical activity may receive inaccurate readings.
- User Experience Enhancements: Implementing a mobile app interface for more personalized tracking.
- Exploring additional physiological indicators (e.g., skin conductance, temperature) for stress detection.
