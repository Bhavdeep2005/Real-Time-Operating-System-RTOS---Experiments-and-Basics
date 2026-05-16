
---

# Experiment 6 – FreeRTOS Single Task LED Blinking

```md
# Experiment 6 – FreeRTOS Single Task LED Blinking

## Objective
To create and execute a single FreeRTOS task for LED blinking.

---

## Theory

FreeRTOS is a lightweight real-time operating system used in embedded applications. Tasks are independent execution units managed by the scheduler.

This experiment demonstrates basic task creation and scheduling using CMSIS-RTOS APIs.

---

## Program Flow

```text
Initialize RTOS Kernel
       ↓
Create Task
       ↓
Start Scheduler
       ↓
Toggle LED in Task
