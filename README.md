
# 🖥️ C++ Task Scheduling Algorithms

## 🌟 Overview  
This repository contains the implementation of various **Task Scheduling Algorithms** in C++. It includes algorithms such as **First-Come-First-Serve (FCFS)**, **Shortest Job First (SJF)**, **Round Robin (RR)**, **Fuzzy Round Robin**, and **Ratio-based Scheduling**. The program reads tasks with arrival times and burst times, processes them, and outputs the scheduling order along with the respective statistics such as completion time, waiting time, and turnaround time.

---

## ✨ Features

### Task Scheduling Algorithms  
- **FCFS (First-Come-First-Serve)**: Processes tasks in the order of their arrival times.
- **SJF (Shortest Job First)**: Prioritizes tasks with the shortest burst time.
- **RR (Round Robin)**: Distributes CPU time among tasks in a round-robin fashion with a time quantum.
- **Fuzzy RR**: A variation of Round Robin with dynamic quantum adjustment based on a fuzzy range.
- **Ratio-Based Scheduling**: Schedules tasks based on a ratio of burst time and arrival time.

### Task Information  
- **Task ID**: Unique identifier for each task.
- **Arrival Time**: Time at which the task arrives.
- **Burst Time**: CPU burst time required by the task.

---

## 🛠️ Technology Stack  

### Programming Language  
- **C++**  

### Compilation  
- **g++** (GNU Compiler Collection)  

---

## 🧩 Algorithm Overview  

### First-Come-First-Serve (FCFS)  
Processes tasks in the order of arrival. It is the simplest scheduling algorithm but can lead to high waiting times for tasks with longer burst times.

### Shortest Job First (SJF)  
Schedules tasks based on the burst time, with the shortest burst time processed first. It is optimal in terms of minimizing waiting time but requires knowledge of burst time in advance.

### Round Robin (RR)  
Each task is assigned a fixed time quantum. If the task does not complete within the quantum, it is pushed back into the queue for the next round.

### Fuzzy Round Robin  
An extension of the RR algorithm where the time quantum is randomly adjusted within a specified fuzzy range, making the scheduling dynamic.

### Ratio-Based Scheduling  
Tasks are prioritized based on a calculated ratio of burst time to the time passed since arrival. This dynamic approach helps improve task prioritization over time.

---

## 🚀 Installation  

### Prerequisites  
- **g++ Compiler**  
- **Linux or MacOS** (for shell script usage)

### Steps to Run the Program

1. Clone the repository or place your `task_scheduler.cpp` file in a directory.
2. Save the provided script as `run_task_scheduler.sh`.
3. Give execution permission to the script:
   ```
   chmod +x run_task_scheduler.sh
  ```

## 📊 Output  
Once executed, the program will display the task scheduling order with completion, turnaround, and waiting times. Example output format:

```text
0ms--(Task:1)--2ms--(Task:3)--5ms--(Task:2)--end
Average Turnaround Time: 4.5 Average Waiting Time: 2.0
```

## 🏆 Future Enhancements
- Add support for **Priority Scheduling** algorithm.
- Improve **UI/UX** to visualize the task scheduling order more intuitively.
- Implement **multi-core CPU scheduling** for better performance and scalability.

---

## 🤝 Contributions
We welcome contributions to enhance the project!

### Steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request with a detailed description of your changes.

---

## 📬 Contact
For any queries or feedback, feel free to reach out at:  
**[a_jaiswal@ece.iitr.ac.in](mailto:a_jaiswal@ece.iitr.ac.in)**.

