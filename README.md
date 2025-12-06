# Vyuha APM — Meta Repository

**Vyuha APM** is a personal, hobby, open-source observability platform created purely for **learning**, **experimentation**, and **showcasing skills**.  
This repository acts as the **meta-repo** for the entire Vyuha ecosystem and contains the architecture, vision, roadmap, and links to all component repositories.

> ⚠️ **Important:** Many modules in this project are **not yet developed** or are **work-in-progress**.  
> This is a personal learning project — **not intended for production use**.

To learn about the full Vyuha APM project architecture, goals, and all related modules, visit the meta repository: https://github.com/nageshdevadig-a/vyuha-apm

---

## 🚀 About the Project

Vyuha APM explores how modern observability platforms work — metrics collection, agents, APIs, storage, AI-based anomaly detection, and dashboards.

It is a **poly-repo system** where each component (agent, server, AI engine, dashboard) lives in its own repository.

Anyone is free to explore, study, modify, or use the project.  
However:

> ⚠️ **No warranties. No guarantees. No responsibility for misuse.**  
> This is a **personal educational project**, not a commercial product.

---

## 📦 Repositories (Poly-Repo Structure)

These repositories represent the major components of Vyuha APM:

### **🖥 Agents**
- **vyuha-host-agent** — Rust system metrics collector *(planned / under development)*  
- **vyuha-jvm-agent** — Java `-javaagent` for JVM metrics *(planned / under development)*  

### **⚙️ Backend Services**
- **vyuha-metrics-server** — Spring Boot metrics ingestion & API server *(WIP)*  
- **vyuha-ai-engine** — Python-based anomaly detection engine *(planned)*  

### **📊 Frontend**
- **vyuha-dashboard** — Web dashboard for visualization *(future component)*  

### **📚 This Repository**
- **vyuha-apm** — Central documentation, architecture, design notes, and cross-repo structure.

> Many components are **not yet implemented**. This meta repository will be updated as development progresses.

---

## 🏗️ System Architecture (Conceptual)

```
[Host Systems]
   |          \
   |           \
[Host Agent]  [JVM Agent]   (planned)
        \         /
         \       /
      [Metrics Server]  (WIP)
             |
             v
      [AI Engine]  (future)
             |
             v
        [Dashboard]  (future)
```

The architecture is modular so each component can be built, deployed, and improved independently.

---

## 🔧 Tech Stack (Planned)

| Component | Technology |
|----------|------------|
| Host Agent | Rust 1.90 |
| JVM Agent | Java 21 |
| Metrics Server | Spring Boot 3.5.x |
| AI Engine | Python 3.12 |
| Dashboard | React / Vue |
| Storage | MySQL / PostgreSQL |
| Communication | REST / HTTP |

---

## 🛠 Why This Project Exists

This project is designed for:

- 📘 **Learning modern observability concepts**  
- 🧠 **Understanding how APM tools like New Relic / Datadog work internally**  
- 💼 **Showcasing skills for interviews and resumes**  
- 🧪 **Experimenting with Rust, Java, Python, ML, and distributed system design**

Not intended for:
- Commercial deployment  
- Handling production workloads  
- Providing service guarantees  

---

## 🧩 Development Status

| Component | Status |
|----------|--------|
| Host Agent (Rust) | **Not yet developed** |
| JVM Agent (Java) | **Not yet developed** |
| Metrics Server | **In progress** |
| AI Engine | **Planned** |
| Dashboard | **Planned** |

This repo will be updated as modules become available.

---

## 🤝 Contributing

Contributions are welcome for learning and experimentation.

- Open issues or discussions in this repo or in the corresponding service repo.
- Not all modules exist yet — contributions may help bootstrap them.
- Since this is a personal learning project, contributions are optional and informal.

---

## ⚠️ Disclaimer

- This is a **personal hobby project**.  
- You may use or modify it freely.  
- The author takes **no responsibility** for outcomes, issues, misuse, or damages.  
- No guarantees are made regarding correctness, security, performance, or reliability.  
- Not affiliated with any company.

---

## 📜 License

Vyuha APM is licensed under the **MIT License**.  
See the full license included below.

---

## 📎 Component Repositories (Links)

Replace `<your-username>` with your actual GitHub username.

| Component | Repository |
|----------|------------|
| Meta Repo | https://github.com/nageshdevadig-a/vyuha-apm |
| Host Agent | https://github.com/nageshdevadig-a/vyuha-host-agent |
| JVM Agent | https://github.com/nageshdevadig-a/vyuha-jvm-agent |
| Metrics Server | https://github.com/nageshdevadig-a/vyuha-metrics-server |
| AI Engine | https://github.com/nageshdevadig-a/vyuha-ai-engine |
| Dashboard | https://github.com/nageshdevadig-a/vyuha-dashboard |

---

## ✉️ Author

**Nagesh Devadiga**  
For questions, open an issue in this repo.

