# Harshil

Software engineer. I work on retrieval and ranking, semantic search, ML serving, and the
distributed backend services underneath them.

Portfolio: [harshilc.com](https://www.harshilc.com)

## Retrieval, ranking & search

**[CineMatch](https://github.com/QHarshil/CineMatch)**
Deployed two-stage recommender. Go API over PostgreSQL with pgvector HNSW retrieval,
feeding a Python LambdaMART re-ranker. 0.814 NDCG@10 vs 0.716 popularity baseline
(offline), ~0.9 ms p95 re-rank. Next.js frontend, JWT auth, RLS on every table.

**[SemanticSearch](https://github.com/QHarshil/SemanticSearch-Java)**
Hybrid retrieval combining BM25 lexical scoring with dense vector similarity. Pluggable
embedding providers.

## ML serving & inference

**[Anytime Inference Planner](https://github.com/QHarshil/Anytime-Inference-Planner)**
Latency-bounded serving. Routes each request to an FP32 or INT8 ONNX variant by live CPU
load with M/M/1 admission control, cutting compute ~45% vs FP32-only.

**[adduce](https://github.com/QHarshil/adduce)**
Static-analysis CLI on PyPI. Traces every number in an ML paper back to the code, config,
data, seed, and environment behind it. 78 rules, plugin API, GitHub Action.

## Systems & quant

**[Execution-Copilot](https://github.com/QHarshil/Execution-Copilot)**
C++ matching engine with TWAP, POV, Almgren-Chriss and PPO execution policies. Backtester
with persistent FIFO limit-order queues and latency modeling.

**[Commerce-Services](https://github.com/QHarshil/Commerce-Services)**
Distributed e-commerce backend: checkout, inventory, orders, payments. Spring Boot,
PostgreSQL, Redis, Kafka inventory events. Built around idempotency and consistency under
partial failure.

**[CRM Donor Engagement Platform](https://github.com/QHarshil/CRM-Donor-Engagement-Platform)**
Full-stack CRM for BC Cancer Foundation. NestJS, React, PostgreSQL, TypeORM. Six-factor
donor ranking with explainable score breakdowns and before/after audit logs.

Also: [FeatureFlagX](https://github.com/QHarshil/FeatureFlagX) (Java/Spring flag service,
Redis cache with PostgreSQL fallback), [TaskRouterX](https://github.com/QHarshil/TaskRouterX)
(cost-aware task scheduler, pluggable FIFO/priority/min-cost algorithms),
[FaceFit](https://github.com/QHarshil/FaceFit-AR-Based-Virtual-Accessory-Try-On)
(browser-based eyewear try-on, MediaPipe Face Mesh and Three.js).

## Competitions

**1st place, Microsoft x Qualcomm On-Device AI Hackathon.** On-device navigation for
wheelchair users, fusing YOLOv8 and Whisper on Snapdragon X Elite at sub-40 ms via DSP/NPU
offloading.

**Top 1% global, IMC Prosperity 2 (rank 87 / 13,500).** Market-making and statistical
arbitrage: regression fair-value estimation, mean-reversion signals, inventory-aware
quoting.

## Stack

**Languages** · Python · Java · C++17/20 · Go · TypeScript · SQL

**ML** · PyTorch · ONNX Runtime · LightGBM · quantization · learning-to-rank ·
pgvector/HNSW · BM25

**Backend** · Spring Boot · FastAPI · gRPC · Kafka · Redis · SNS/SQS · idempotent
consumers · event-driven architecture

**Data** · PostgreSQL (query-plan tuning, indexing) · Aurora PostgreSQL · Elasticsearch
(kNN/BM25) · Liquibase

**Cloud & tooling** · AWS (ECS/Fargate, Lambda, SNS/SQS, S3, Aurora) · Docker · CI/CD ·
pybind11 · CMake
