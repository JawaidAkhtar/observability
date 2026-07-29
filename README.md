# 📊 Cloud Native Observability Stack using Prometheus, Grafana & Loki

<p align="center">
  <img src="https://img.shields.io/badge/Prometheus-Monitoring-E6522C?style=for-the-badge&logo=prometheus" />
  <img src="https://img.shields.io/badge/Grafana-Dashboard-F46800?style=for-the-badge&logo=grafana" />
  <img src="https://img.shields.io/badge/Loki-Log%20Aggregation-F2CC0C?style=for-the-badge&logo=grafana" />
  <img src="https://img.shields.io/badge/Promtail-Log%20Collector-2D3748?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker" />
  <img src="https://img.shields.io/badge/Observability-Cloud%20Native-blue?style=for-the-badge" />
</p>

---

# 📌 Project Overview

This repository demonstrates a **Cloud Native Observability Stack** built using **Prometheus**, **Grafana**, **Loki**, **Promtail**, **Node Exporter**, and **cAdvisor**.

The monitoring stack is deployed using **Docker Compose** and provides complete visibility into application health, host performance, Docker containers, and centralized log management.

The project showcases how modern DevOps teams monitor containerized applications using open-source observability tools.

---

# 💼 Business Problem

Running containerized applications without monitoring makes it difficult to identify performance bottlenecks, infrastructure issues, and application failures.

Organizations require a centralized observability platform that provides real-time metrics, infrastructure monitoring, container monitoring, and log aggregation to maintain application reliability and reduce troubleshooting time.

---

# 💡 Solution

This project implements a complete monitoring stack using Docker Compose.

The stack continuously collects metrics from the application, Docker containers, and host machine while aggregating logs into a centralized platform.

Grafana provides interactive dashboards for visualization, Prometheus collects metrics, and Loki stores application logs for troubleshooting and analysis.

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Monitoring | Prometheus |
| Visualization | Grafana |
| Log Aggregation | Loki |
| Log Collection | Promtail |
| Container Monitoring | cAdvisor |
| Host Monitoring | Node Exporter |
| Containerization | Docker |
| Orchestration | Docker Compose |
| Application | Weather App |
| Cache | Redis |

---

# ✨ Key Features

- 📈 Infrastructure Monitoring
- 📊 Real-Time Dashboards
- 🐳 Docker Container Monitoring
- 💻 Host Resource Monitoring
- 📄 Centralized Log Collection
- 🔍 Log Aggregation using Loki
- 📥 Log Collection using Promtail
- 📦 Docker Compose Deployment
- 🌐 Unified Monitoring Network
- 🚀 Cloud Native Observability

---

# 📦 Services Included

## Weather Application

The sample application generates application traffic and metrics for monitoring.

---

## Redis

Provides backend caching service for the application.

---

## Prometheus

Responsible for collecting metrics from all monitoring targets.

Monitors:

- Weather App
- Node Exporter
- cAdvisor

---

## Grafana

Visualizes metrics and logs using interactive dashboards.

Provides:

- Infrastructure Dashboard
- Container Dashboard
- Application Dashboard
- Log Dashboard

---

## cAdvisor

Collects Docker container metrics including:

- CPU Usage
- Memory Usage
- Network Statistics
- Disk Utilization
- Running Containers

---

## Node Exporter

Collects host-level metrics including:

- CPU
- Memory
- Disk
- Filesystem
- Network
- Load Average

---

## Loki

Centralized log storage for all application logs.

---

## Promtail

Collects logs from the Docker host and forwards them to Loki.

---

# 🏗️ Monitoring Architecture

<img width="1536" height="1024" alt="ChatGPT Image Jul 29, 2026, 10_45_50 PM" src="https://github.com/user-attachments/assets/2860aba5-0ebb-45e2-b09e-14b24418c5ce" />


# 🚀 Deployment Guide

## Clone Repository

```bash
git clone https://github.com/JawaidAkhtar/observability.git

cd observability
```

---

## Start Monitoring Stack

```bash
docker compose up -d
```

---

## Verify Running Containers

```bash
docker ps
```

---

## Access Services

| Service | URL |
|----------|-----|
| Weather App | http://localhost:5000 |
| Prometheus | http://localhost:9090 |
| Grafana | http://localhost:3000 |
| cAdvisor | http://localhost:8080 |
| Node Exporter | http://localhost:9100 |
| Loki | http://localhost:3100 |

---

# 👨‍💻 Author

**Jawaid Akhtar**

AWS Cloud | DevOps Engineer | Docker | Kubernetes | Observability

- GitHub: https://github.com/JawaidAkhtar
- LinkedIn: https://www.linkedin.com/in/jawaidakhtar/
