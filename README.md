# CPU Scheduling Simulator & Operating Systems Virtual Lab

An interactive, self-contained **CPU Scheduling Simulator and Virtual Laboratory** built with pure HTML5, CSS3, and modern JavaScript. Designed with an elegant **Forest Green + Warm Beige** aesthetic.

![Pure HTML/JS](https://img.shields.io/badge/Language-HTML5%20%7C%20CSS3%20%7C%20JavaScript-2d6a4f?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-None%20(Pure%20Vanilla)-1b4332?style=flat-square)
![Offline](https://img.shields.io/badge/Mode-100%25%20Offline-b27f3c?style=flat-square)

---

## 🌟 Key Features

- **7 CPU Scheduling Algorithms**:
  - **FCFS** (First-Come, First-Served)
  - **SJF (Non-Preemptive)** (Shortest Job First)
  - **SRTF** (Shortest Remaining Time First / Preemptive SJF)
  - **Priority (Non-Preemptive)** (Configurable priority order)
  - **Priority (Preemptive)**
  - **Round Robin (RR)** (Configurable Time Quantum $q$)
  - **Multilevel Feedback Queue (MLFQ)**: 3 dynamic priority tiers ($Q_0$: RR, $Q_1$: RR, $Q_2$: FCFS) with preemption and queue demotion.
- **Visual Interactive Gantt Chart**:
  - Color-coded process execution blocks with duration tooltips.
  - Distinct hatched pattern for **CPU Idle** states.
  - High-visibility terracotta tracker needle with time scrub scrubber ($t = 0 \to T_{\text{total}}$).
  - Playback controls: Play, Pause, Step Forward (+1), Step Backward (-1), Jump to Start/End, and Speed multiplier ($0.5\times$ to $4.0\times$).
- **Live Hardware State Visualizer**:
  - Real-time **CPU Core** state (displays current active process or idle status).
  - Dynamic **Ready Queue** display showing queued processes and remaining burst times.
  - Multi-tier visualizer for **MLFQ** queues ($Q_0$, $Q_1$, $Q_2$).
- **Process Set Configurator & Presets**:
  - Add, edit, or delete custom processes with PID, Arrival Time (AT), Burst Time (BT), and Priority.
  - 5 One-Click Presets: *Standard Academic Mix*, *Convoy Effect Demo*, *Priority Starvation Demo*, *Round Robin Time Slicing*, and *CPU Idle Gaps*.
  - Configurable context switch overhead delay.
- **Comprehensive Performance Metrics**:
  - Live calculations for **Completion Time (CT)**, **Turnaround Time (TAT)**, **Waiting Time (WT)**, and **Response Time (RT)**.
  - Summary cards: Average TAT, Average WT, Average RT, CPU Utilization %, and Throughput.
- **Step-by-Step Plain English Operation Log**:
  - Explanatory timeline log documenting every arrival, context switch, preemption, quantum expiration, and process completion.
- **Complete Educational Laboratory Manual**:
  - **AIM & Objectives** conforming to university curricula.
  - **Mathematical Formulas & Theory**:
    $$\text{TAT} = \text{CT} - \text{AT}$$
    $$\text{WT} = \text{TAT} - \text{BT}$$
    $$\text{RT} = \text{First Allocation} - \text{AT}$$
  - **Algorithm Comparative Matrix**.
  - **Formal Pseudo-Code** for FCFS, SRTF, and Round Robin.
  - **Production-Ready C Code** implementations with syntax presentation and one-click copy buttons.
  - **Standard Benchmark Test Cases** for calculation verification.
  - **Viva Voce & FAQ Accordion** covering Convoy Effect, starvation, aging, quantum trade-offs, and MLFQ.

---

## 🎨 Theme & Design

The user interface is designed with a **Forest Green + Warm Beige** palette:
- **Canvas**: Soft Linen Beige (`#f5f0e6`)
- **Cards**: Warm Ivory Cream (`#fdfbf7`) with subtle sand borders (`#dfd7c5`)
- **Primary Accent**: Deep Forest Green (`#1e4d2b`)
- **Processes**: Nature-inspired earth tone spectrum (Deep Forest, Golden Ochre, Emerald Pine, Terracotta Clay, Sage Leaf, Warm Chestnut, Dark Fir, Golden Sand, Moss Green, Wild Heather)
- **Code Blackboard**: Deep Evergreen Pine (`#122419`)

---

## 🚀 Getting Started

No installation, build tools, or web server required.

1. Clone this repository:
   ```bash
   git clone https://github.com/Rohannn2960/CPU-scheduling-simulator.git
   cd CPU-scheduling-simulator
   ```
2. Double-click or open `index.html` in any web browser (Chrome, Edge, Firefox, Safari).

---

## 📄 License

Open-source and free for academic, classroom, and educational use.
