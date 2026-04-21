##  Automated Web Infrastructure & Monitoring Lab

##  Project Overview
This project demonstrates the deployment of a containerized web server and its integration into an enterprise-grade monitoring system (**Zabbix 7.0 LTS**) on **Ubuntu 24.04**.

* **Containerization:** Apache web server deployed via Docker and managed with Docker Compose.
* **Infrastructure Monitoring:** Real-time telemetry using Zabbix Agent 2 with Docker-socket integration.
* **Alerting:** Automated notification pipeline via Telegram Bot Webhooks.
* **Infrastructure as Code:** All configurations are version-controlled and documented for rapid deployment.

## 🛠 Technical Stack
* **OS:** Ubuntu 24.04 LTS (Noble Numbat)
* **Containers:** Docker, Docker Compose
* **Monitoring:** Zabbix 7.0 LTS
* **Web:** Apache (httpd:2.4-alpine)
* **Networking:** Port mapping (8082:80), DNS basics, HTTP/HTTPS.
* **Monitor:** Zabbix agent is pre-configured to monitor the Docker socket.
