# Advanced Monitoring & Alerting Stack

A full monitoring solution using:

-  Prometheus (metrics)
-  Grafana (dashboards)
-  Loki & Promtail (logs)
-  Alertmanager (alerts)
-  Slack Integration (notifications)

##  Quick Start

1️⃣ Create your Slack Incoming Webhook URL  
2️⃣ Replace it in `alertmanager/config.yml`  
3️⃣ Run:

```bash
docker-compose up --build

## Access Services
Prometheus → http://localhost:9090

Grafana → http://localhost:3000 (user: admin / pass: admin)

Loki API → http://localhost:3100

Alertmanager → http://localhost:9093

## Dashboards
Create data sources in Grafana for both Prometheus & Loki

Build custom dashboards for full observability

## Author
ViorelH — Project 10: Full Observability Stack with Alerting