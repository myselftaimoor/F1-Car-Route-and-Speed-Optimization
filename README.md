# Reinforcement Learning for Autonomous Formula 1 Car Navigation

This repository contains the implementation of a **reinforcement learning (RL) framework** developed for autonomous **Formula 1 car navigation**. Leveraging **NEAT (NeuroEvolution of Augmenting Topologies)** and **PyGame** for simulation, the project focuses on optimizing racing lines, decision-making, and vehicle control for autonomous racing.

The system employs a **genetic algorithm** to evolve neural networks over generations, enabling virtual cars to learn optimal strategies for lap completion. It simulates 100 cars across 20 generations, with each generation improving upon the last based on performance metrics such as lap time and obstacle avoidance.

---

## 📝 Research Paper

The framework is based on the research paper titled "**Optimizing Route Efficiency in Formula One (F1) Vehicles Using Reinforcement Learning Algorithms**", presented at the **4th IEEE International Conference on AI in Cyber Security (2025)**.

- **Paper DOI**: [IEEE Publication Link](https://ieeexplore.ieee.org/document/10848611)
- **Authors**: Dr. Sanam Narejo, Muhammad Taimoor Khan, Dr. Muhammad Zakir Shaikh, Prof. Dr. Bhawani Shankar Chowdhery, Dr. Lubna Luxmi Dhirani 
---

## 🏎️ Features

- **NeuroEvolution of Augmenting Topologies (NEAT)** for evolving neural networks
- **Simulated Environment**: PyGame for dynamic track simulation
- **100 Virtual Cars**: Trained simultaneously over **20 generations**
- **Genetic Algorithm**: Cars with faster lap times or better decision-making are prioritized in the evolutionary process
- **Improved Performance**: Achieved optimized racing lines, lap times, and obstacle avoidance

---

## 🧠 Methodology

1. **Training Environment**: A virtual F1 track is created using PyGame, where cars navigate autonomously.
2. **Reinforcement Learning**: Cars learn from their actions using **reward-based feedback**.
3. **NEAT Algorithm**: Neural networks evolve over multiple generations, with better-performing networks passed to the next generation.
4. **Performance Metrics**: Each generation is evaluated on lap times, racing line efficiency, and obstacle avoidance.

---

## 📦 Installation & Setup

1. **Clone the Repository**  
   ```bash
     git clone https://github.com/yourusername/f1-rl-navigation.git
     cd f1-rl-navigation

2. **Create & Activate Virtual Environment**
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt

4. **Run the Simulation**
    ```bash
    python game.py

## 🛠️ Tech Stack

- Programming Language: Python

- Reinforcement Learning: NEAT, PyGame

- Libraries: NumPy, PyGame, TensorFlow, Keras

- Simulation Environment: PyGame-based 2D F1 racing track

- Machine Learning: NEAT for evolving neural networks over generations

## 🤝 Contributing

- Contributions are welcome! If you want to contribute, feel free to open a pull request.

- For major changes, please open an issue to discuss before making changes.

## 📄 License

This project is licensed under the MIT License.


