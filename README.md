# 🧠 Harshil Chudasama

**ML Systems Engineer** bridging the gap between distributed infrastructure and high-performance machine learning.  

🎓 MSCS (AI/ML) Candidate

I build systems that are **resilient at scale** and **optimized for latency**. My work focuses on the intersection of Backend Engineering, ML Infrastructure, and Quantitative Systems.

---

## ⚡ Engineering Focus
I don't just write code; I design systems with specific constraints:
* **Distributed Consistency**: Implementing patterns like **Saga** and **Optimistic Concurrency Control** to ensure data integrity in event-driven architectures.
* **High-Performance ML**: Optimizing inference pipelines using **Quantization (INT8)**, **ONNX Runtime**, and shared memory IPC to hit sub-50ms deadlines.
* **Algorithmic Complexity**: simulating market microstructure and building **Contextual Bandit** agents for decision-making under uncertainty.
* **Reliability**: Designing for failure with **Circuit Breakers**, **Backpressure**, and **Idempotency**.

---

## 🛠 Featured Projects

### 📈 [Execution Copilot](https://github.com/QHarshil/Execution-Copilot)
**Role:** Quant Dev & Systems Architect  
*A low-latency algorithmic trading engine and market simulator.*
* **The Tech:** C++, Python, Linear Algebra, Reinforcement Learning.
* **The System:** Implemented **lock-free ring buffers** to handle high-throughput tick data with minimal GC pauses.
* **The Math:** Utilized **Contextual Bandits (LinUCB)** for smart order routing, validated via walk-forward backtesting on 5 years of historical data.

### ⏱️ [Anytime Inference](https://github.com/QHarshil/Anytime-Inference---ML-Model-Serving)
**Role:** ML Systems Engineer  
*A deadline-aware inference router for resource-constrained environments.*
* **The Tech:** Python, PyTorch, ONNX Runtime, Hugging Face.
* **The System:** Architected a scheduler that dynamically swaps model quantization levels (FP32 vs. INT8) based on real-time **CPU pressure**.
* **The Impact:** Guarantees **sub-50ms p99 latency** for concurrent user loads, validated via stress testing.

### 🛒 [Commerce Services](https://github.com/QHarshil/Commerce-Services)
**Role:** Backend Engineer  
*A distributed e-commerce platform built for scale.*
* **The Tech:** Java (Spring Boot), Kafka, PostgreSQL, Kubernetes, Redis.
* **The System:** Engineered an event-driven architecture using the **Saga Pattern** for distributed transactions across microservices.
* **The Impact:** Implemented **Optimistic Concurrency Control (OCC)** to prevent race conditions, reducing database deadlocks by 40% (verified via chaos engineering).

### 🚩 [FeatureFlagX](https://github.com/QHarshil/FeatureFlagX)
**Role:** Platform Engineer  
*A scalable experimentation platform for A/B testing.*
* **The Tech:** Java, Redis, Docker, Consistent Hashing.
* **The System:** Designed a deterministic user bucketing engine using **Consistent Hashing** to ensure stable experiment assignment.
* **The Impact:** Achieved **<10ms evaluation latency** with a multi-layer caching strategy (Local + Redis).

---

### Notable Projects

- **[FaceFit AR](https://github.com/QHarshil/FaceFit-AR-Based-Virtual-Accessory-Try-On)** | `Computer Vision`, `Three.js`, `React.js`, `Node.js`: Browser-based eyewear try-on. It integrates MediaPipe Face Mesh for dense 3D facial landmark extraction with a Three.js rendering pipeline that places GLB eyewear models directly onto the user video stream.
- **[Full-Stack CRM - Event and Donor Management](https://github.com/QHarshil/Full-Stack-CRM---Events-and-Donor-Management)** | `NestJS`, `React`, `TypeORM`, `Socket.IO`, `PostgreSQL`: Donor operations suite with multi-criteria matching, real-time fundraising dashboards, role-aware access, and compliance-grade audit logging that trimmed vetting time **40%**.
- **[TaskRouterX](https://github.com/QHarshil/TaskRouterX)** | `FastAPI`, `Python`, `SQLite`: **Cost-aware task routing** with pluggable schedulers, live dashboard, synthetic load generator, and pytest coverage.

---

## 🏆 Competitions & Awards

* **IMC Prosperity 2 Trading Competition**: **Global Rank 87th / 30,000 (Top 0.3%)**.
    * *Engineered Python-based market-making algorithms utilizing Monte Carlo simulations to optimize risk-reward ratios in a volatile exchange.*
* **Microsoft x Qualcomm On-Device AI Hackathon**: **1st Place Winner**.
    * *Optimized real-time navigation pipelines on Snapdragon NPUs by leveraging DSP offloading for combined Vision+Audio models.*

---

## 🧰 Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Java, Python, C++, TypeScript, SQL |
| **Backend & Systems** | Spring Boot, FastAPI, Kafka, Redis, PostgreSQL, gRPC |
| **Infrastructure** | AWS (Lambda, ECS), Kubernetes, Docker, Terraform |
| **AI & Math** | PyTorch, ONNX, YOLOv8, NumPy, Stochastic Processes |

---

<div align="center">
  <p><i>Open to roles in Backend Engineering, Distributed Systems, and ML Infrastructure.</i></p>
</div>
