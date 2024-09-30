node-exporter
# Monitoring Tools

This project includes the following monitoring tools:

- **cAdvisor**: Analyzes resource usage and performance characteristics of running containers.
- **Grafana**: Provides dashboards and visualizations for time-series data.
- **Prometheus**: A monitoring system and time-series database.
- **Alertmanager**: Handles alerts sent by client applications such as Prometheus.

## Getting Started

To get started with these tools, follow the instructions below.

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:
  ```sh
  git clone /home/dtu/project/monitoring
  cd monitoring
  ```

2. Start the services:
  ```sh
  docker-compose up -d
  ```

### Usage

- Access Grafana at `http://localhost:3000`
- Access Prometheus at `http://localhost:9090`
- Access Alertmanager at `http://localhost:9093`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

