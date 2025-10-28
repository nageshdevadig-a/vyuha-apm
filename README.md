# Vyuha APM

**Vyuha APM** is a next-generation, AI-driven observability platform designed for real-time system monitoring, anomaly detection, and intelligent insights.  
It combines lightweight agents, a scalable backend, and predictive analytics to deliver complete visibility across your infrastructure.

---

## 🏗️ System Architecture

- **Host Agent (Rust / Java)** — Collects system-level and JVM metrics from host machines and containers.  
- **Metrics Server (Spring Boot)** — Aggregates, stores, and exposes APIs for metrics ingestion and querying.  
- **AI Engine (Python)** — Performs anomaly detection, trend analysis, and predictive insights on collected data.  
- **Dashboard (Web)** — Provides real-time visualization, health insights, and alert analytics for monitored systems.

---

## ⚙️ Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Agents** | Rust 1.80+, Java 21 |
| **Server** | Spring Boot 3.5+, Gradle |
| **AI Engine** | Python 3.12, Scikit-learn / PyTorch |
| **Dashboard** | React / Vue, TypeScript |
| **Storage** | PostgreSQL / MySQL |
| **Communication** | REST APIs, HTTP / gRPC (planned) |

---

## 🌟 Key Features

- 🧩 **Modular Microservice Architecture** — Independent agents and services for easy scalability.  
- ⚡ **Real-time Metrics Collection** — CPU, memory, disk, and network performance tracking.  
- 🧠 **AI-Powered Insights** — Detects anomalies and predicts performance degradation.  
- ☁️ **Cloud-Ready & Lightweight** — Built for containerized and distributed environments.  
- 📊 **Interactive Dashboard** — Real-time visualization of health and performance.  
- 🔌 **Extensible Design** — Easy integration with third-party APMs and tools.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/nageshdevadig-a/vyuha-apm.git
cd vyuha-apm
```

### 2. Run Locally
- Start **Metrics Server**:  
  ```bash
  cd server
  ./gradlew bootRun
  ```
- Launch **Host Agent** or **JVM Agent**:  
  ```bash
  cargo run --bin vyuha-host-agent
  ```
- Start **AI Engine**:
  ```bash
  python ai_engine/main.py
  ```
- Open the **Dashboard** in your browser.

---

## 🧩 Planned Enhancements

- Distributed tracing and log ingestion  
- gRPC-based high-performance data pipeline  
- Agent-side caching and batching  
- Dynamic rule-based alerting  
- Container-level metrics collection  

---

## 🪪 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute it under open-source terms.  
Please give credit if you use it in your own work.

---

## 🙏 Disclaimer

Vyuha APM is a personal learning and research project aimed at exploring observability, APM design, and intelligent system monitoring.  
It is **not affiliated with any organization** and should be used for educational or experimental purposes only.

---

## 💡 Author

**Nagesh Devadiga**  
Aspiring Observability & APM Engineer | Builder of intelligent monitoring tools  
[GitHub](https://github.com/nageshdevadig-a)
