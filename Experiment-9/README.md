
---

# Experiment 9 – Inter-Task Communication using Message Queue

```md
# Experiment 9 – Inter-Task Communication using Message Queue

## Objective
To implement inter-task communication using RTOS message queues.

---

## Theory

Message queues allow safe data transfer between RTOS tasks. One task acts as producer while another acts as consumer.

In this experiment, sensing task generates distance values and sends them through queue to navigation task.

---

## Program Flow

```text
Producer Task Generates Data
       ↓
Data Stored in Queue
       ↓
Consumer Task Reads Queue
       ↓
Display Received Data
