<h1 align="center">Krish Jain</h1>

<p align="center">
  <b>B.Tech Electrical Engineering · IIT Jodhpur</b><br/>
  Building systems where rigorous math meets real-world autonomy —<br/>
  from safe RL controllers to autonomous UAVs, power grids, and AI-powered web platforms.
</p>

<p align="center">
  <a href="mailto:b24ee1097@iitj.ac.in">
    <img src="https://img.shields.io/badge/Email-b24ee1097%40iitj.ac.in-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Krish-Jain-IITJ">
    <img src="https://img.shields.io/badge/GitHub-Krish--Jain--IITJ-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## What I Build

```
Autonomous Systems   →  Drones, rovers, unicycle robots with safe navigation
Reinforcement Learning →  DQN, SAC, residual RL, curriculum training
AI Platforms         →  RAG pipelines, LLM agents, full-stack Django/FastAPI apps
Simulation           →  Gazebo, ROS 2, Raylib, ZeroMQ-bridged C++/Python
Control Theory       →  BLF, CBF, PID, hybrid classical + learned controllers
```

---

## Selected Projects

### 🚁 [Autonomous UAV Navigation System](https://github.com/Krish-Jain-IITJ/Project1_autonomous_drone)
Real-time autonomous drone navigation with 2.5D occupancy-grid mapping, A* global path planning, and LiDAR + depth camera fusion. Fully integrated with **ROS 2**, **PX4 Offboard**, and **Gazebo** simulation.
- 82–87% navigation success rate in cluttered indoor corridors
- <150 ms obstacle detection-to-action latency
- Continuous A* replanning at 2 Hz with dynamic replanning on map updates

`Python` `ROS 2` `PX4` `Gazebo` `A*` `LiDAR` `Sensor Fusion`

---

### 🤖 [Residual RL for Obstacle Avoidance](https://github.com/Krish-Jain-IITJ/rl_unicyclic_model) · *IEEE 2026*
Hybrid BLF + SAC architecture for unicycle robots. Classical controller handles baseline tracking; RL agent intervenes only near obstacles via a soft-gating function.
- **99.96%** collision-avoidance rate · **>98%** path fidelity
- Staged 4-phase curriculum: single → dual → tri → high-density obstacles
- Hyperparameter tuning via Optuna (100-trial multi-objective campaign)

`PyTorch` `SAC` `Gymnasium` `Optuna` `Control Theory` `Python`

---

### ⚡ [Power Grid DQN](https://github.com/Krish-Jain-IITJ/Power_Grid)
DQN agent managing a 50-substation power grid over a full year (8,760 h) of simulated operation. High-performance C++ simulator bridged to Python via ZeroMQ.
- 4-action discrete space: NO_ACTION, REROUTE, THROTTLE_10%, THROTTLE_20%
- 24-hour regional overload penalty to prevent policy exploitation
- Dynamic observation sizing via handshake — topology-agnostic

`C++` `Python` `ZeroMQ` `DQN` `Gymnasium` `Raylib` `CMake`

---

### 🌕 [Mission Chandrendra — Lunar Ice Detection](https://github.com/Krish-Jain-IITJ)
End-to-end pipeline from radar remote sensing to autonomous landing on the Moon.
- DFSAR/MidAS radar analysis → CPR & DOP filtering → ice volume estimation (~23.6M m³)
- BLF + Residual RL guided helical drone descent (tracking error e ≈ 0.018)
- Rover deployment with circular safety-set obstacle avoidance

`Python` `QGIS` `Gazebo` `Control Theory` `Remote Sensing`

---

### 🧠 [Agentic RAG Chatbot](https://github.com/Krish-Jain-IITJ/Rag_chatbot)
Local-first RAG chatbot at the intersection of NLP and accessible AI — no cloud subscription required.

`Python` `LangChain` `ChromaDB` `FastAPI`

---

### 📚 [Circuit Theory AI Platform](https://github.com/Krish-Jain-IITJ/Circuit-Theory)
Django web platform for circuit theory learning with conversational AI, RAG, symbolic math, and CV-based circuit diagram analysis.

`Django` `LangGraph` `ChromaDB` `OpenAI` `OpenCV` `MediaPipe` `SymPy`

---

### 📊 [Monday.com BI Agent](https://github.com/Krish-Jain-IITJ/skylark_drones_ps_re)
FastAPI-powered BI assistant with live Monday.com GraphQL integration, short-term conversational memory, and real-time tool trace panel.

`FastAPI` `Anthropic Claude` `GraphQL` `Python` `HTML/CSS/JS`

---

## Publications

📄 **"Multiple Obstacle Avoidance and Trajectory Tracking via Residual Reinforcement Learning on Arbitrary Control"**
Krish Jain, Suhaib Md., Anoop Jain (IIT Jodhpur) · *IEEE, 2026*

---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### ML / RL / AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=for-the-badge&logo=openai&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Robotics & Simulation
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-000000?style=for-the-badge&logo=px4&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)

### Web & Backend
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

### Tools & Infra
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![ZeroMQ](https://img.shields.io/badge/ZeroMQ-DF0000?style=for-the-badge&logo=zeromq&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Krish-Jain-IITJ&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Krish-Jain-IITJ&layout=compact&theme=github_dark&hide_border=true" height="160"/>
</p>

---

<p align="center">
  <i>"The goal is not to replace the engineer — it is to build systems rigorous enough to be trusted."</i>
</p>
