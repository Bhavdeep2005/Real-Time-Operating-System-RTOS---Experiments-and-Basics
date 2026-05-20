
---

# Experiment 7 – Multitasking using FreeRTOS

```md
# Experiment 7 – Multitasking using FreeRTOS

## Objective
To understand RTOS task priority scheduling using multiple tasks.

---

## Theory

FreeRTOS scheduler executes higher priority tasks before lower priority tasks. In this experiment, two LED tasks are created with different priorities.

Task execution order demonstrates RTOS priority-based scheduling behavior.

---

## Program Flow

```text
Create High Priority Task
       ↓
Create Low Priority Task
       ↓
Start Scheduler
       ↓
Tasks Execute According to Priority
