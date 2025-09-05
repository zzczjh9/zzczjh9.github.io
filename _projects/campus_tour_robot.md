---
layout: project
title: "Campus Tour Robot"
date: 2024-06-15
image: /assets/img/campus_robot_demo.gif
alt_text: "Autonomous Campus Tour Guide Robot"
project_url: https://github.com/zzczjh9/campus-tour-robot
github_repo: zzczjh9/campus-tour-robot
summary: "Award-winning autonomous robot with vision, voice, and cloud integration for campus tours"
category: projects
importance: 4
selected: true
---

## Overview

This project won the **Best Robotic Project Prize** at Imperial College for the second year cohort. The autonomous campus tour guide robot integrates advanced robotics, computer vision, and cloud technologies to provide interactive campus tours.

## Key Features

- **Self-balancing Mobility**: Dual-loop PID/LQR control achieving <15cm positional accuracy and 3s disturbance recovery
- **Reinforcement Learning**: Developed TD3 reinforcement learning in Gazebo with BARN dataset for trajectory following
- **Computer Vision**: YOLOv8 Nano vision system integrated on RK3588 achieving >90% person-tracking accuracy at <100ms latency
- **Cross-platform Control**: Flutter app for robot control with real-time weather sensing (GY-39/GPS)
- **Cloud Infrastructure**: Deployed AWS EC2 cloud infrastructure with JWT-secured REST API, PostgreSQL, and ReactJS dashboard
- **Voice Assistant**: Implemented RAG-enhanced voice assistant using OpenAI API with on-device MP3 playback via ESP32 I2S

