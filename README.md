# Autonomous Mobile Robot for Smart Parking Management

## Project Overview
This project aims to develop an autonomous mobile robot capable of:
- Identifying available and occupied parking spots.
- Navigating autonomously while avoiding obstacles.
- Generating a real-time dynamic parking map.

The system integrates **computer vision, embedded systems, and robotics algorithms** to enhance parking efficiency and reduce CO₂ emissions caused by unnecessary vehicle movement.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Concept](#project-concept)
3. [Hardware Components](#hardware-components)
4. [Mathematical Models & Algorithms](#mathematical-models--algorithms)
5. [Software & Programming](#software--programming)
6. [Implementation & Results](#implementation--results)
7. [Discussion & Future Improvements](#discussion--future-improvements)
8. [How to Run the Project](#how-to-run-the-project)

---

## Introduction
### **Context and Objectives**
Urban parking management is a growing challenge due to the increasing number of vehicles. Drivers often struggle to find available parking spots, leading to:
- Increased fuel consumption.
- Higher CO₂ emissions.
- Unnecessary traffic congestion.

This project aims to provide an **automated solution** to optimize parking space management by using a mobile robot to **detect available spots, avoid obstacles, and update a real-time parking map**.

### **Value Added**
- **Innovative Solution**: Enhances parking efficiency through automation.
- **Low-Cost Implementation**: Uses **Raspberry Pi, Arduino, and LIDAR** for affordability.
- **Modular Design**: Can integrate future features like **license plate recognition**.
- **Eco-Friendly Approach**: Reduces unnecessary vehicle movements and emissions.

---

## Project Concept
### **Problem Statement**
Urban areas suffer from poor parking space management due to a **lack of automation** and **real-time monitoring**. This leads to **inefficient space usage, increased search time, and environmental impact**.

### **Proposed Solution**
Our **Autonomous Mobile Robot**:
1. **Scans parking spaces** using a **camera and sensors**.
2. **Identifies available and occupied spots**.
3. **Navigates autonomously** while avoiding obstacles.
4. **Updates a digital parking map** in real-time.

---

## Hardware Components
| Component | Description |
|-----------|------------|
| **Chassis** | 4-wheel mobile robot chassis for stability and mobility |
| **Motors & Driver** | DC motors controlled via L293D driver shield |
| **Raspberry Pi** | Main processing unit for image analysis and control |
| **Arduino Uno** | Handles sensor data processing |
| **Camera (Raspberry Pi 3)** | Captures images to detect vehicles |
| **LIDAR (TF Luna)** | Detects obstacles and measures distances |
| **Ultrasonic Sensors** | Assist in obstacle avoidance |
| **Servo Motor** | Controls camera movement for scanning |
| **Lithium Batteries & Powerbank** | Provides power to the system |

---

## Mathematical Models & Algorithms
### **Detection of Parking Spaces & Obstacles**
- **Matrix-based parking representation**.
- **Obstacle avoidance using ultrasonic sensors**.
- **Real-time map updates based on detected vehicles**.

### **Car Detection Algorithm**
- Uses **computer vision (OpenCV)** to detect vehicles.
- Updates the **dynamic parking map** with captured data.

---

## Software & Programming
### **Programming Languages**
- Python (Raspberry Pi processing)
- C++ (Arduino sensor control)

### **Libraries Used**
| Library | Function |
|---------|----------|
| OpenCV | Image processing for car detection |
| NumPy | Matrix representation of parking spaces |
| RPi.GPIO | Raspberry Pi GPIO control |
| Arduino Libraries | Motor & sensor communication |

---

## Implementation & Results
### **Development Stages**
1. **Hardware assembly** (chassis, motors, sensors, camera).
2. **Sensor & motor integration** (LIDAR, ultrasonic sensors).
3. **Image processing implementation** (car detection via OpenCV).
4. **Autonomous navigation development**.
5. **Testing & validation**.

### **Limitations**
- Lack of **wheel encoders** affects precise positioning.
- **Environmental conditions** (lighting, obstacles) impact detection.

### **Results**
- Successfully **identified available & occupied parking spots**.
- Efficiently **avoided obstacles**.
- Generated a **real-time parking map**.

---

## Discussion & Future Improvements
### **Strengths**
- **Low-cost, scalable solution** for smart parking management.
- **Real-time, dynamic parking updates**.
- **Autonomous navigation & obstacle avoidance**.

### **Limitations**
- Lacks **GPS localization** for larger parking areas.
- Requires **improved object recognition** for night-time performance.

### **Future Enhancements**
- Integrate **license plate recognition**.
- Improve **AI-based navigation**.
- Deploy in **larger parking environments**.

---
