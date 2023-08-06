# prometheus-cadvisor-docker-grafana
Monitor the docker containers using Prometheus-Grafana-Cadvisor

# Prerequisites
Docker & docker-compose installed 

# Purposes
Prometheus - datasource for Grafana to monitor.
Grafana - To visualize the metrics of containers.
cAdvisor - To export docker metrics.
Redis - Demo container.

# Setup
Run "docker-compose up -d" to get the stack up and running.

# Access
Grafana - http://localhost:3000
Prometheus - http://localhost:8080
cAdvisor - http://localhost:9090

# Bonus Tip
Import dashboard in Grafana with id - "193" to monitor all containers on a single pane of window.

Happy Monitoring!!!

