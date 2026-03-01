# Hi, I'm Dileep 👋

AI Engineer building secure, production-grade ML and GenAI systems on AWS.

My work sits at the intersection of machine learning, distributed systems, and cloud architecture. I’m particularly interested in building AI systems that are not just intelligent — but observable, scalable, and safe to run in real-world environments.

---

## What I Focus On

- LLM infrastructure & AI security
- Retrieval-Augmented Generation (RAG) systems
- Real-time ML inference platforms
- Quantitative ML systems with governance controls
- Cloud-native AI architecture (AWS + Terraform)

I care about performance benchmarking, model reliability, and infrastructure reproducibility just as much as model accuracy.

---

## Flagship Projects

### 🔐 Secure LLM Gateway

A production-style middleware layer in front of large language models.

It handles:

- Prompt injection detection (embedding-based classifier with async micro-batching)
- Role-based model access control (RBAC)
- PII detection and response redaction
- Token usage tracking and cost estimation
- Prometheus instrumentation
- Concurrency benchmarking (~475 req/sec tested)

The goal was to design a safe, governed LLM deployment layer — something closer to enterprise reality than a demo app.

Repository:  
https://github.com/dileepkreddy5/secure-llm-gateway

---

### 🧩 Enterprise Hybrid Graph-RAG

A hybrid retrieval architecture combining:

- Multi-hop graph reasoning
- Vector similarity search
- Weighted ranking strategy
- Retrieval evaluation metrics (Precision@K, Recall@K, MRR)
- Latency instrumentation
- Claude integration (Bedrock-ready design)

This project focuses on explainability and measurable retrieval quality — not just “LLM answers.”

Repository:  
https://github.com/dileepkreddy5/graph-rag-enterprise

---

### ⚡ Real-Time ML Feature Store

A production-style inference system designed around training-serving parity.

- Online/offline feature consistency
- Redis for online serving, Parquet for offline training
- Streaming ingestion (Redpanda)
- Multi-worker FastAPI inference
- ~7 ms p50 latency, ~2.6K req/sec sustained load

This project explores low-latency ML deployment and real-time system performance.

Repository:  
https://github.com/dileepkreddy5/real-time-ml-feature-store

---

### 📈 QuantEdge — Quantitative AI Platform

An institutional-style quantitative analysis system deployed end-to-end on AWS.

Core components include:

- 8 ML/statistical models (LSTM, XGBoost, LightGBM, HMM, GJR-GARCH, Kalman, Ensemble)
- Triple-barrier labeling (Lopez de Prado)
- Regime detection (5-state HMM)
- Independent risk engine (CVaR, shrinkage covariance, volatility targeting)
- Portfolio construction via HRP
- Governance layer with Deflated Sharpe Ratio (DSR)
- Full infrastructure-as-code using Terraform
- ECS Fargate backend, Redis caching, Cognito + MFA, WAF hardening

The emphasis here is systems rigor — model governance, risk isolation, and reproducible cloud deployment.

Live system:  
https://quant.dileepkapu.com

---

## Tech Stack

**Languages**  
Python · SQL · TypeScript  

**AI / ML**  
PyTorch · Scikit-learn · XGBoost · LightGBM  
LangChain · Vector Databases · RAG Architectures  
Feature Stores · Model Serving · Retrieval Evaluation  

**Cloud & Infrastructure**  
AWS (ECS, S3, RDS, Redis, Cognito, WAF, CloudFront, Bedrock)  
Terraform · Docker · GitHub Actions  

**Observability & Performance**  
Prometheus · Latency Instrumentation  
Concurrency Benchmarking · Micro-batching Optimization  

---

## Certifications

- AWS Certified Machine Learning – Specialty  
  https://www.credly.com/badges/d6246db1-de09-4018-8bff-c6f21a842acc/public_url  

- AWS Certified Solutions Architect – Professional  
  https://www.credly.com/badges/695dc576-6be5-4f16-8dc7-0698469a68c4/public_url  

- HashiCorp Terraform Associate  
  https://www.credly.com/badges/54ebe779-5438-418d-8385-c7c309c6b860/public_url  

---

## Current Interests

- Secure LLM architectures
- AI governance & model reliability
- Retrieval quality benchmarking
- Cost-aware GenAI systems
- Real-time ML infrastructure design

---

## Connect

LinkedIn: https://www.linkedin.com/in/kapu-dileep-kumar-reddy-1084301a9/

Portfolio: https://dileepkapu.com

Email: dileepkreddy5@gmail.com

