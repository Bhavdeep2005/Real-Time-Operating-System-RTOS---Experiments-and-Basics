# Experiment 10 – Mutex Synchronization

## Objective
To implement mutex synchronization for shared resource protection in FreeRTOS.

---

## Hardware Required
- STM32F446RE Nucleo Board
- LEDs

---

## Software Used
- STM32CubeIDE
- FreeRTOS
- STM32 HAL Drivers

---

## Introduction
Mutexes prevent simultaneous access to shared resources and avoid race conditions.

---

## Procedure
1. Create multiple tasks.
2. Create mutex object.
3. Lock mutex before resource access.
4. Release mutex after execution.

---

## Working
Tasks access shared resources safely using mutex locking mechanism.

---

## Result
Mutex synchronization using FreeRTOS was successfully implemented.
