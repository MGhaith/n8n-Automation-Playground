# n8n Automation Playground

A comprehensive n8n automation platform with integrated monitoring and observability capabilities using Grafana and Prometheus.

## Quick Start

This project runs in a local development environment.

**Local Development Environment**
    
Prerequisites:
- [Docker](https://docs.docker.com/get-started/get-docker/) installed on your machine
    
Setup steps:
1. Create your environment file by copying the example:
   ```bash
   cp .env.example .env
   ```
2. Configure the environment variables in `.env`
3. Start the containers:
   ```bash
   docker compose -f docker-compose.yml -f docker-compose.monitoring.yml up -d --build
   ```
4. Access the services:
   - n8n interface: [http://localhost:5678](http://localhost:5678)
   - Grafana dashboard: [http://localhost:3000](http://localhost:3000)

Monitoring Features:
- Pre-configured Grafana dashboards for n8n metrics (n8n Health overview and infra overview)
- System resource utilization tracking
- Automated datasource provisioning for Prometheus
