# 🚗 Automotive CAN Data Parser & Visualization Platform

A high-performance, web-based tool for decoding CAN 2.0 messages and visualizing vehicle signals in real-time.

---

## ✨ Key Features
* **DBC Lifecycle Management**: Upload, parse, and manage `.dbc` files with an embedded SQLite database.
* **High Performance**: Decode **1,000+ messages in <50ms** using a optimized Java 17 engine.
* **Signal Visualization**: Interactive ECharts integration for multi-signal curve analysis (Zoom/Drag/Export).
* **Developer Friendly**: Clean architecture with **Spring Boot 3.2** and **Vue 3 (Vite)**.
* **Bilingual Support**: Instant toggle between English and Chinese UI.

---

## 📸 Screenshots
![Main Interface](./screenshots/main_ui.png)
![Signal Analysis](./screenshots/charts.png)

---

## 🛠️ Tech Stack
| Layer | Framework / Tool |
| :--- | :--- |
| **Backend** | Java 17, Spring Boot 3.2, Spring Data JPA |
| **Frontend** | Vue 3.0, Vite, Element Plus, ECharts |
| **Database** | SQLite (Zero-configuration) |

---

## 🚀 Getting Started

### 1. Backend Setup
1. Ensure **JDK 17** is installed.
2. Navigate to `/backend` and run:
   ```bash
   mvn clean compile
   mvn spring-boot:run
2. Frontend Setup
Ensure Node.js (v18+) is installed.

Navigate to /frontend and run:

Bash

npm install
npm run dev
📄 License & Source Code
This project is available in different tiers (Standard/Developer/Enterprise).
To access the full source code and commercial license, please visit:
👉 Get it on Gumroad

Note: This platform currently supports CAN 2.0 (Standard/Extended). CAN-FD is not supported.
