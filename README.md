![BroFOSS](https://user-images.githubusercontent.com/13851773/35186632-04654536-fe3d-11e7-98d6-9bf5dc273840.png)

[![Join the chat at https://gitter.im/BroFOSS/BroFOSS](https://badges.gitter.im/BroFOSS/BroFOSS.svg)](https://gitter.im/BroFOSS/BroFOSS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Join mailing list at https://groups.google.com/forum/#!forum/brofoss](https://img.shields.io/badge/Mailing%20List-BroFOSS-blue.svg)](https://groups.google.com/forum/#!forum/brofoss)

Welcome to the **BroFOSS** - An Initiative of Open Source Technologies using Computer Science, Electrical, and Electronics concepts.

Our primary focus is to work on free and open-source software (FOSS), open hardware design and to let the world contribute and share. Most of the projects here are targeted to increase easiness, safety, and security of our daily lives. You can find projects which include creation of Android / IOS apps to creation of automatic lighting facility for automobiles. As we are also focusing on open hardware design it will be a great opportunity for all to develop open source embedded software.

We are applying for the first time to Google Summer of Code 2018. Below are some list of ideas for students to apply for, but not limited to it. We are open to new ideas, feel free to discuss them in our [google group](https://groups.google.com/forum/#!forum/brofoss). 

## Contents
1. [New Idea Template](#new-idea-template)
2. [Potential Mentors](#potential-mentors)
3. [Potential Ideas](#potential-ideas)
   - [STM32-Driver (Microcontroller+Embedded-System+STM32)](#1-low-level-driver-for-stm32-series-microcontroller-using-embedded-c)
   - [STM32-GRBL (Microcontroller+Embedded-System+STM32+CNC)](#2-porting-the-grbl-cnc-library-of-arduino-to-stm32-series)
   - [Safe Navigator (IOT + Android)](#3-safe-navigator-iot--android)
   - [E-voting (Cryptography + Web)](#4-e-voting-cryptography--web)
   - [E-voting (Cryptography + Android)](#5-e-voting-cryptography--android)
   - [Moto Navigator (IOT + Android)](#6-moto-navigator-iot--android)

4. [Proposal Template](#proposal-template)

## 1. New Idea Template
**Please use the below idea template to mention ideas:**

***

**Idea:**

(Mention your idea here.)

**Software / Technologies involved:**

(Mention the technologies and/or software your idea contain.)

***

## 2. Potential Mentors
* Anupam Das ([opticod](https://github.com/opticod)) (anupam.das.bwn@gmail.com)
* Arnab Kumar Das ([arnabdasbwn](https://github.com/arnabdasbwn)) (arnab.das.bwn@gmail.com)

We are also open to new potential mentors, who wants to join us.

## 3. Potential Ideas

### 1. Low-Level Driver for STM32 Series Microcontroller using Embedded C

**Idea:**

The HAL library provides by STMicroelectronics for its STM32 Series is bulky and is too complexly designed with a lot of middle layers. So we are looking for creating open-source low-level drivers for all the On-Chip Peripherals of the Microcontroller. We are primarily targeting STM32F4 Series but we are happy with any series starting from STM32L0 Series to STM32F7. Our focus will be developing the lowest layer with Register Access. 

**Technologies:**

Microcontroller, Embedded System, STM32

### 2. Porting the GRBL CNC Library of Arduino to STM32 Series 

**Idea:**

(Existing open source code repo: https://github.com/BroFOSS/grbl-coreXY-servo)

The Arduino GRBL library works on AVR8 at 16Mhz with a slow motor driving speed and slow processing. Whereas Industrial Standard speed is very high and demands performance. It will be an awesome Open-Source project to port the GRBL to STM32F4 or STM32F7 Microcontroller with an Increased Performance due to Higher Clock and Better Bus Architecture and advance on-chip peripherals. We will also focus on adding all G-Code and M-Code Support.

**Technologies:**

Microcontroller, Embedded System, STM32, CNC

### 3. Safe Navigator (IOT + Android)

**Idea:**

In many places including cities in India, people face road accidents in winter due to poor visibility from fog. Our idea is to build, a navigation based app which will alert and suggest the users on the road to stop/reduce their speed of their vehicle, when there is sudden congestion in front of them, using p2p based techniques. At the same time, the privacy of all users should also be taken care. 

**Technologies:** 

Android Development, Google Map API / Mapbox API, Google Cloud Platform / Any other scalable server approach.

Video links to sample accidents to prevent: [Youtube link](https://www.youtube.com/watch?v=CaZWmFWZ_L0)

### 4. E-voting (Cryptography + Web)

**Idea:**

In many institutions, we still use the manual based voting system, where a user is required to go to a place and write his/ her vote in a paper, and then submit in a box. After few weeks, the results are declared using manual counting. Our idea to create an open source, secure, e-voting system, which can be used by such different institutions to automate their processes. 

**Technologies:**

Web Development, Cryptography.

### 5. E-voting (Cryptography + Android)

**Idea:**

**(Android mobile version of Idea 4)**

In many institutions, we still use the manual based voting system, where a user is required to go to a place and write his/ her vote in a paper, and then submit in a box. After few weeks, the results are declared using manual counting. Our idea to create an open source, secure, e-voting system, which can be used by such different institutions to automate their processes. 

**Technologies:**

Android Development, Cryptography.

### 6. Moto Navigator (IOT + Android)

**Idea:**

(Existing open source android app repo: https://github.com/BroFOSS/Moto-Navigator)

Create an Arduino/ Raspberry Pi/ BeagleBone based system, which will automate the lightning of any motor vehicle. Once the system is paired with the Android app, it will send different signals using Bluetooth/ wifi, to the system to turn various lightings on, depending on its location, road orientation, and heading direction.

**Technologies:**

Arduino/ Raspberry Pi/ BeagleBone, Android Development.


## 4. Proposal Template

**Please use the below proposal template:**

***

Project Name  - 

Name - 

Contact info - 

Contents - 
1. Abstract
2. Project Idea or Issues to consider
3. Analysis and Proposed Solutions
4. UI Designs / Wire-frames (if needed, optional)
5. Timeline
6. About Yourself

***
