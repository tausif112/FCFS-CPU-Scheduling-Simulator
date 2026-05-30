<div align="center">

# 🚀 FCFS CPU Scheduling Simulator

### First Come First Serve (FCFS) Scheduling Algorithm Implementation in Python

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)](https://www.python.org/)
[![Operating Systems](https://img.shields.io/badge/Operating%20Systems-FCFS-green?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

<br>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tausif112/FCFS-CPU-Scheduling-Simulator/blob/main/FCFS.ipynb)

</div>

---

# 📌 Project Overview

This project demonstrates the implementation of the **First Come First Serve (FCFS)** CPU Scheduling Algorithm, one of the most fundamental scheduling techniques used in Operating Systems.

The simulator executes processes in the order they arrive and calculates:

* ✅ Process Waiting Time
* ✅ Average Waiting Time
* ✅ Gantt Chart Representation
* ✅ Execution Timeline

The project was developed and tested using **Google Colaboratory (Google Colab)** and later published on GitHub as part of an Operating Systems learning portfolio.

---

# 🧠 About FCFS Scheduling

FCFS (First Come First Serve) is a **non-preemptive CPU scheduling algorithm** where the process that arrives first gets executed first.

### Advantages

* Simple and easy to implement
* Fair process ordering
* Minimal scheduling overhead

### Disadvantages

* Can lead to long waiting times
* Suffers from the Convoy Effect
* Not suitable for time-sharing systems

---

# ⚙️ Algorithm

1. Initialize the current time as 0.
2. Execute processes sequentially according to arrival order.
3. Calculate the waiting time of each process.
4. Update the current execution time.
5. Generate the Gantt Chart.
6. Calculate Average Waiting Time.

---

# 🧮 Input Example

```python
processes = [
    ('P1', 21),
    ('P2', 3),
    ('P3', 6),
    ('P4', 2)
]
```

# 📊 Output Example

```text
Gantt Chart: 0 P1 21 P2 24 P3 30 P4 32

Average Waiting Time: 18.75
```

---

# 📈 Gantt Chart

```text
0          21      24      30      32
|----P1----|--P2--|---P3---|-P4-|
```

---

# ☁️ Development Environment

This project was implemented and tested using:

* Python 3
* Google Colaboratory (Google Colab)
* GitHub

### Google Colab Workspace

![Colab Workspace](screenshots/colab-workspace.png)

---

# 📸 Program Output

![Output](screenshots/output.png)

---

# 📂 Project Structure

```text
FCFS-CPU-Scheduling-Simulator/
│
├── FCFS.ipynb
├── fcfs.py
├── README.md
├── LICENSE
├── .gitignore
│
└── screenshots/
    ├── colab-workspace.png
    └── output.png
```

---

# 🚀 How to Run

## Clone the Repository

```bash
git clone https://github.com/tausif112/FCFS-CPU-Scheduling-Simulator.git
```

## Navigate to Project Directory

```bash
cd FCFS-CPU-Scheduling-Simulator
```

## Run the Program

```bash
python fcfs.py
```

---

# 📋 Sample Calculation

| Process | Burst Time | Waiting Time |
| ------- | ---------- | ------------ |
| P1      | 21         | 0            |
| P2      | 3          | 21           |
| P3      | 6          | 24           |
| P4      | 2          | 30           |

### Average Waiting Time

```text
(0 + 21 + 24 + 30) / 4

= 75 / 4

= 18.75
```

---

# 🔮 Future Improvements

* Arrival Time Support
* Turnaround Time Calculation
* Response Time Calculation
* Priority Scheduling
* Shortest Job First (SJF)
* Round Robin Scheduling
* Graphical Gantt Chart Visualization
* Interactive User Input

---

# 🛠 Technologies Used

| Technology                 | Purpose                     |
| -------------------------- | --------------------------- |
| Python                     | Core Implementation         |
| Google Colab               | Development Environment     |
| GitHub                     | Version Control             |
| Operating Systems Concepts | Scheduling Logic            |

---

# 🎯 Learning Outcomes

Through this project, the following concepts were explored:

* CPU Scheduling Algorithms
* Process Management
* Waiting Time Calculation
* Gantt Chart Construction
* Python Programming
* GitHub Project Management

---

# 👨‍💻 Author

**Md. Tausif Uddin**

Bachelor of Science in Computer Science and Engineering (CSE)

University of Asia Pacific (UAP)

GitHub: https://github.com/tausif112

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
