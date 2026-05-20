# Real-Time-Operating-System-RTOS---Experiments-and-Basics

## Description
A comprehensive collection of embedded system and RTOS laboratory experiments performed using STM32F446RE. This repository covers fundamental embedded concepts such as GPIO interfacing, button input, ultrasonic sensor interfacing, PWM generation, and advanced FreeRTOS concepts including task scheduling, semaphores, queues, mutex, interrupts, and real-time task management.

---

## Overview

This repository contains a collection of RTOS-based experiments implemented on the STM32F446RE Nucleo development board using STM32CubeIDE and FreeRTOS.

The experiments are designed to provide practical understanding of:
- GPIO interfacing
- Timer and PWM applications
- Sensor interfacing
- Task scheduling
- Multitasking concepts
- Inter-task communication
- Synchronization mechanisms in RTOS

Each experiment demonstrates a specific embedded systems concept with proper source code, configuration files, and project structure.

---

## Hardware Platform

- STM32F446RE Nucleo Board
- ARM Cortex-M4 Microcontroller
- Onboard LEDs and Push Buttons
- HC-SR04 Ultrasonic Sensor
- IR Sensor
- USB ST-Link Programmer

---

## Software Requirements

- STM32CubeIDE
- STM32 HAL Drivers
- FreeRTOS Middleware
- STM32CubeMX Configuration Tool

---

# Repository Structure

| Experiment No. | Experiment Name |
|----------------|----------------|
| Experiment 1 | LED Blinking using GPIO |
| Experiment 2 | Push Button Interfacing |
| Experiment 3 | Ultrasonic Sensor Interfacing |
| Experiment 4 | PWM Generation using Timer |
| Experiment 5 | Time-Based Scheduling without RTOS |
| Experiment 6 | Single Task using FreeRTOS |
| Experiment 7 | Multitasking using FreeRTOS |
| Experiment 8 | Binary Semaphore in FreeRTOS |
| Experiment 9 | Message Queue Communication |
| Experiment 10 | Mutex Synchronization |

---

# Experiment Descriptions

## Experiment 1 – LED Blinking
Basic GPIO output interfacing using STM32 HAL library to blink onboard LED with delay functions.

---

## Experiment 2 – Push Button Interfacing
Reading digital input from push button and controlling LED based on switch status.

---

## Experiment 3 – Ultrasonic Sensor Interfacing
Distance measurement using HC-SR04 ultrasonic sensor with UART serial monitoring.

---

## Experiment 4 – PWM Signal Generation
Generation of PWM signals using STM32 timer peripheral and dynamic duty cycle variation.

---

## Experiment 5 – Cooperative Task Scheduling
Execution of multiple periodic tasks without RTOS using system tick timing.

---

## Experiment 6 – Single Task using FreeRTOS
Creation and execution of a single FreeRTOS task for LED control.

---

## Experiment 7 – Multitasking using FreeRTOS
Implementation of two concurrent tasks with different priorities for multitasking demonstration.

---

## Experiment 8 – Binary Semaphore
Synchronization between interrupt service routine and task using binary semaphore.

---

## Experiment 9 – Message Queue Communication
Inter-task communication using FreeRTOS message queues for producer-consumer implementation.

---

## Experiment 10 – Mutex Synchronization
Protection of shared resources using mutex mechanism in FreeRTOS.

---

# Features

- STM32 HAL-based development
- FreeRTOS task scheduling
- Peripheral interfacing
- UART debugging
- Semaphore and mutex synchronization
- Queue-based communication
- Real-time embedded programming concepts

---

# Development Environment

| Tool | Purpose |
|------|----------|
| STM32CubeIDE | Code Development |
| STM32CubeMX | Peripheral Configuration |
| FreeRTOS | RTOS Kernel |
| ST-Link | Programming and Debugging |

---

# Learning Outcomes

After performing these experiments, the following concepts can be understood:
- Real-Time Operating Systems
- Embedded multitasking
- Task synchronization
- Inter-task communication
- Timer and PWM applications
- Peripheral interfacing techniques
- Embedded firmware development

---

# Author

Bhavdeep Singh

---

# License

This repository is created for educational and academic purposes.

---

