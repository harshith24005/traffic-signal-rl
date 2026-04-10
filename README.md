# 🚦 Traffic Signal Optimization using Reinforcement Learning

## 📌 Overview

This project demonstrates how **Reinforcement Learning (RL)** can be used to optimize traffic signal control at a junction.
The goal is to **minimize vehicle waiting time** by dynamically adjusting traffic signals based on real-time traffic conditions.


## 🧠 Problem Statement

Traditional traffic signals use fixed timing, which is inefficient under varying traffic conditions.
This project implements a **Q-Learning based RL agent** that learns to control traffic signals intelligently.


## ⚙️ Methodology

### 🔹 Algorithm Used

* Q-Learning (Tabular Reinforcement Learning)

### 🔹 State Representation

* Number of cars in each direction:

  * North, South, East, West

### 🔹 Actions

* 0 → North-South Green Signal
* 1 → East-West Green Signal

### 🔹 Reward Function

* Negative of total waiting cars:

  * Encourages reducing congestion


## 🔄 Workflow

1. Initialize traffic queues
2. Cars arrive randomly
3. RL agent selects signal
4. Vehicles pass based on signal
5. Calculate reward
6. Update Q-table
7. Repeat for multiple episodes


## 🛠️ Technologies Used

* Python 🐍
* NumPy
* Matplotlib


## 📊 Results

* The RL agent learns to reduce waiting time over episodes
* Performance improves compared to random signal selection

📈 Output Graph:
(Add your screenshot here)


## 📁 Project Structure

```bash
traffic-signal-rl/
│── traffic_signal_rl.ipynb
│── README.md
│── output.png
```


## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/harshith24005/traffic-signal-rl.git
```

2. Navigate to the folder:

```bash
cd traffic-signal-rl
```

3. Run the Python file:

```bash
python traffic_signal_rl.py
```

OR open Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📸 Screenshots

(Add screenshots of simulation and graph here)


## 🎯 Conclusion

This project shows how reinforcement learning can improve traffic signal efficiency by adapting to dynamic traffic conditions, reducing congestion and waiting time.


## 🔮 Future Work

* Implement Deep Q-Network (DQN)
* Multi-intersection traffic control
* Real-time traffic data integration

