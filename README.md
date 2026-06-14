# Shinkansen AI Swarm: Autonomous Disaster-Resilient Railway System

**India's Smart Railway + Drone Swarm for Disaster Management**  
**FAR AWAY 2026 Hackathon Project**

![Project Banner](https://via.placeholder.com/800x300?text=Shinkansen+AI+Swarm)

---

## 🎯 One Line Pitch
An **AI-powered multi-agent system** that transforms Indian Railways into an intelligent, autonomous, disaster-resilient network using drone swarms — inspired by Japan’s Shinkansen safety systems.

---

## 🚄 Problem Statement
India faces frequent floods, earthquakes, and cyclones that disrupt railway operations and delay emergency response. Current systems are slow and manual. Japan’s Shinkansen has world-class earthquake detection. Our project bridges this gap by combining **Railways + Logistics + Agentic AI**.

---

## ✨ Key Features

### Software (Round 1 - Completed)
- Multi-Agent AI System (Prediction, Routing, Drone Swarm Agents)
- Real-time Dashboard + Disaster Simulation
- Computer Vision for obstacle/survivor detection
- Autonomous decision making using LangGraph / CrewAI

### Hardware (Planned for Offline Round)
**Custom Control Board: Shinkansen Swarm Control Board v1.0**

- **Microcontroller**: ESP32-WROOM-32
- **Motor Driver**: L298N (for miniature train)
- **Power Management**: AMS1117-3.3
- **Sensors**: SW-420 Vibration Sensor (Earthquake detection)
- **Camera**: OV2640 Camera Module (Computer Vision)
- **Drone Interface**: Dedicated ESC connectors for drone swarm

**KiCad Files**: [Schematic](Shinkansen_Swarm_Control_Board.pdf.pdf) | [PCB](hardware/Shinkansen_Swarm_Control_Board.kicad_pcb)

![Schematic](hardware/schematic.png)
![3D View](hardware/3d_view.png)

---

## 🛠️ Tech Stack

**Software**
- Backend: FastAPI + Python
- AI Agents: LangGraph
- Frontend/Dashboard: Streamlit
- Computer Vision: OpenCV

**Hardware**
- KiCad (Schematic + PCB Design)
- ESP32, L298N, Sensors & Camera Modules
- Future: 3D Printed Train Chassis + Drone Landing Platform

---

## 📁 Project Structure
