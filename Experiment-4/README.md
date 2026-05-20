
---

# Experiment 4 – PWM Signal Generation

```md
# Experiment 4 – PWM Generation using Timer

## Objective
To generate PWM signals using STM32 timers for LED brightness control.

---

## Components Required

- STM32F4 Board
- LEDs
- STM32CubeIDE
- STM32CubeMX

---

## Theory

PWM (Pulse Width Modulation) is widely used for motor speed control and LED brightness adjustment. STM32 timers generate PWM signals by varying duty cycle.

In this experiment, TIM2 generates PWM outputs on two channels. Duty cycle gradually increases and decreases to create fading effect.

---

## Software Used

- STM32CubeIDE
- STM32 HAL Drivers

---

## Program Flow

```text
Initialize Timer PWM
       ↓
Start PWM Channels
       ↓
Increase Duty Cycle
       ↓
Decrease Duty Cycle
       ↓
Repeat
