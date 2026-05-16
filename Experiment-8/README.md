
---

# Experiment 8 – Binary Semaphore using FreeRTOS

```md
# Experiment 8 – Binary Semaphore using FreeRTOS

## Objective
To synchronize tasks using binary semaphore in FreeRTOS.

---

## Theory

Semaphores are synchronization mechanisms used for signaling between interrupts and tasks. In this experiment, button interrupt releases a binary semaphore.

The LED task waits for semaphore and toggles LED after receiving signal.

---

## Program Flow

```text
Button Interrupt Occurs
       ↓
Semaphore Released
       ↓
Task Acquires Semaphore
       ↓
LED Toggles
