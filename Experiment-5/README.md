
---

# Experiment 5 – Time Sharing Based Task Scheduling

```md
# Experiment 5 – Time Sharing Based Task Scheduling

## Objective
To implement software-based time sharing using periodic task execution.

---

## Theory

Time sharing allows multiple tasks to execute periodically without blocking the processor. Different counters are used to schedule LED blinking, button monitoring, and ADC sensor reading independently.

This experiment demonstrates cooperative multitasking using system tick timing.

---

## Components Required

- STM32F4 Board
- IR Sensor
- Push Button
- UART Terminal

---

## Program Flow

```text
Get System Tick
       ↓
Update Task Counters
       ↓
Execute Periodic Tasks
       ↓
Repeat
