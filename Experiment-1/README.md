# Experiment 1 – LED Blinking using GPIO

## Objective
To interface an LED with STM32F4 microcontroller and perform LED blinking using GPIO output mode.

---

## Components Required

- STM32F4 Discovery/Nucleo Board
- STM32CubeIDE
- USB Cable
- Onboard LED

---

## Theory

GPIO (General Purpose Input Output) pins are used for digital input and output operations in embedded systems. In this experiment, GPIO pin PA5 is configured as output mode to drive an LED.

The STM32 microcontroller continuously toggles the LED state with a software delay, creating a blinking effect. This experiment introduces GPIO initialization, digital output control, and basic HAL functions.

---

## Software Used

- STM32CubeIDE
- STM32 HAL Drivers

---

## Program Flow

```text
Initialize HAL
       ↓
Configure System Clock
       ↓
Initialize GPIO
       ↓
Toggle LED
       ↓
Delay
       ↓
Repeat
