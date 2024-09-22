
**Folder Structure**

**docker-compose.yml**: Docker Compose file to deploy Grafana, Prometheus, and any necessary services.

**prometheus.yml**: Configuration for Prometheus, defining how it scrapes metrics from your services and what endpoints to monitor.

**dashboards/**: Contains Grafana dashboard JSON files, which can be imported into your Grafana instance to immediately get useful visualizations.

The docker-compose.yml file will spin up both Prometheus and Grafana. In this file, you'll likely need to adjust the volume paths depending on where your data is stored on your host machine.
