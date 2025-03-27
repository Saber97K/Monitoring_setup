Observability Stack with Docker – Monitoring and tracing setup for backend services

Technologies: Docker, Docker Compose, Grafana, Prometheus, OpenTelemetry, Loki, Tempo

Built a full observability stack to monitor API performance, logs, and traces

Configured Grafana dashboards, Prometheus metrics scraping, Loki log aggregation, and Tempo distributed tracing, all orchestrated via docker-compose

Automated setup and teardown with PowerShell scripts using docker ps -q | ForEach-Object { docker stop $_; docker rm $_ }
