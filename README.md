# Operating-Systems-CPU-Scheduling

![Course](https://img.shields.io/badge/Course-SE%20418%20Operating%20Systems-2F5597)
![Topic](https://img.shields.io/badge/Topic-CPU%20Scheduling%20Algorithms-4F81BD)
![Institution](https://img.shields.io/badge/University-UBT-1F3864)

## Overview
This repository contains my solutions for **Assignment: Operating Systems (CPU Scheduling)**.

The assignment covers four core CPU scheduling algorithms, complete with spreadsheet-based Gantt charts and step-by-step turnaround time and waiting time calculations across **12 questions (Q1–Q12)**.

---

## Repository Contents

* **`Nasser Alharbi - YA0708 - Sec11 - Assignment 3.pdf`** — Complete assignment submission containing the problem tables, color-coded Gantt charts, and step-by-step mathematical solutions for all 12 questions.

---

## Summary of Scheduling Algorithms & Results

*(All processes are assumed to arrive at `0 ms`.)*

| Questions | Scheduling Algorithm | Execution Order (Gantt Chart) | Avg. Turnaround Time | Avg. Waiting Time |
| :--- | :--- | :--- | :---: | :---: |
| **Q1 – Q3** | **Shortest-Job-First (SJF)** *(Non-Preemptive)* | `P3 (0–1)` → `P2 (1–5)` → `P4 (5–10)` → `P1 (10–17)` | **8.25 ms** | **4 ms** |
| **Q4 – Q6** | **Priority Scheduling** *(Non-Preemptive, 1 = Highest)* | `P2 (0–2)` → `P4 (2–5)` → `P1 (5–11)` → `P3 (11–19)` | **9.25 ms** | **4.5 ms** |
| **Q7 – Q9** | **Round Robin (RR)** *(Time Quantum = 3 ms)* | `P1 (0–3)` → `P2 (3–6)` → `P3 (6–8)` → `P4 (8–11)` → `P1 (11–13)` → `P2 (13–14)` → `P4 (14–17)` → `P4 (17–18)` | **13.25 ms** | **8.75 ms** |
| **Q10 – Q12** | **First-Come, First-Served (FCFS)** | `P1 (0–6)` → `P2 (6–9)` → `P3 (9–17)` → `P4 (17–19)` | **12.75 ms** | **8 ms** |

---

## Formulas Used

* **Turnaround Time:** $\text{Completion Time} - \text{Arrival Time}$
* **Waiting Time:** $\text{Turnaround Time} - \text{CPU Burst Time}$
* **Average Time:** $\frac{\sum \text{Process Times}}{\text{Number of Processes}}$

---

## Author
**Nasser Tariq Alharbi**  
Department of Software Engineering — University of Business and Technology (UBT)
