# Cloud-Ready Observability & Security Stack 🚀

This project demonstrates a production-grade monitoring and logging infrastructure built with **Docker**, designed to provide real-time visibility and security auditing for containerized environments.

## 🛠 Tech Stack
* **Prometheus**: Time-series metrics collection and alerting.
* **Grafana**: Advanced data visualization and security dashboards.
* **Loki**: Log aggregation system for forensic analysis and intrusion detection.
* **Docker & Docker Compose**: Container orchestration for high portability.

## 🛡 Security First Approach
* **Environment Management**: Implementation of `.env` files to keep sensitive credentials out of the source code.
* **Version Control Hygiene**: Strict use of `.gitignore` to prevent data leaks and follow industry best practices.
* **Log Auditing**: Configured Loki to monitor SSH attempts and system access, enabling rapid response to unauthorized activity.

## 📊 Key Features
* **Real-time Dashboards**: Visualizing system health, CPU/RAM usage, and network traffic.
* **Automated Alerting**: Integration with notification platforms for critical system events.
* **Scalable Architecture**: Modular design that can easily integrate with AWS (CloudWatch/CloudTrail) or hybrid infrastructures.

## 🚀 How to Run
1. Clone the repository.
2. Create your `.env` file based on the `.env.example` provided.
3. Run `docker-compose up -d`.
4. Access Grafana at `http://localhost:3000`.
