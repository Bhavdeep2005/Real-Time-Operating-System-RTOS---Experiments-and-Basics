
---

# Experiment 3 – Ultrasonic Sensor Interfacing with UART

```md
# Experiment 3 – Ultrasonic Sensor Interfacing with UART

## Objective
To measure distance using HC-SR04 ultrasonic sensor and display the measured value over UART.

---

## Components Required

- STM32F4 Board
- HC-SR04 Ultrasonic Sensor
- UART Terminal
- STM32CubeIDE
- STM32CubeMX

---

## Theory

The HC-SR04 ultrasonic sensor measures distance using ultrasonic sound waves. The TRIG pin sends a pulse while the ECHO pin returns the reflected signal duration.

The STM32 measures echo pulse width using timer-based microsecond delay and calculates distance using speed of sound formula.

UART communication is used to display measured distance on serial terminal.

---

## Software Used

- STM32CubeIDE
- STM32 HAL Drivers
- UART Terminal

---

## Program Flow

```text
Generate Trigger Pulse
       ↓
Wait for Echo Signal
       ↓
Measure Echo Width
       ↓
Calculate Distance
       ↓
Send Data via UART
