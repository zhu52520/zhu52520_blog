---
title: Media Bluetooth Keyboard Development Based on ESP32C3
date: 2022-08-28T09:08:00.000Z
draft: false
featured: false
tags:
  - Embedded System
  - Self-motivation Project
links:
  - url: https://github.com/zhu52520/Media-Bluetooth-Keyboard-Development-Based-on-ESP32C3
    name: Github
    icon_pack: fab
    icon: github
image:
  filename: img_20220828_165913.jpg
  focal_point: Smart
  preview_only: false
---
Reviewed hid Bluetooth protocol, FreertOS architecture, lithium battery charge, and discharge design;

Tested the relationship curve between lithium battery power and output voltage;

Drew the schematic diagram of the keyboard, including the peripheral of the chip, charge and discharge, automatic burning, battery protection, power monitoring, and key signal filtering;

Used ICEDA to draw the PCB and completed the soldering;

Used SolidWorks to draw the keyboard shell and produced it by metal 3D printing;

Used ESP-IDF to complete the programming part, realized the crossplatform multimedia function by adjusting the Bluetooth protocol code, and further filtered the key signal through the algorithm