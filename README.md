
# SSH Log Monitoring and Alerting Docker-compose Setup

Welcome to the SSH Log Monitoring and Alerting Docker Setup! This project provides a streamlined Docker Compose configuration for monitoring SSH logs and setting up alerts for successful connections.

## Features

- Docker Compose setup for monitoring SSH logs.
- Configured alerting for successful SSH connections.
- Easy configuration process requiring minimal setup.

## Prerequisites

- Docker installed on your system.
- Docker Compose installed on your system.

## Getting Started

1. Clone this repository to your local machine:

```
git clone https://github.com/SalaheddineS/PromtLokiGrafana_SSH_Alerting_And_Monitoring.git
```

2. Navigate to the cloned repository:

```
cd PromtLokiGrafana_SSH_Alerting_And_Monitoring
```

3. Fill in the required configurations:

   - Open `alertmanager-config/alertmanager.yml` and configure your smtp credentials

4. Once configuration is set, start the services using Docker Compose:

```
docker-compose up -d
```

5. Access Grafana and Alertmanager:

   - Grafana: [http://localhost:3000](http://localhost:3000) then add a dashboard using this id : `17514`
   - Alertmanager: [http://localhost:9093](http://localhost:3100)

6. You can now begin monitoring SSH logs and receive alerts for successful connections.

## Customization

Feel free to customize the configurations to suit your specific needs. You can explore further options and integrations offered by Prometheus, Grafana, Loki, and Alert Manager.

## Troubleshooting

If you encounter any issues or have questions, feel free to open an issue in this repository. i'll be happy to assist you!

