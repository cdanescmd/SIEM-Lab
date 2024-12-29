# SIEM-Lab
## SIEM Implementation and Log Analysis Lab

This lab provides a hands-on environment for experimenting with SIEM (Security Information and Event Management) tools using an ELK stack (Elasticsearch, Logstash, Kibana). Analyze logs, detect patterns, and gain insights into security threats in a simulated environment.

## Features

- Analyze web server logs using Elasticsearch and Kibana.
- Explore log ingestion, filtering, and visualization using Logstash.
- Experiment with real-world log analysis scenarios (e.g., failed login attempts, unauthorized access).
- Simulate a production-like SIEM setup.

## Prerequisites

- [Docker](https://www.docker.com/get-started) installed and running
- Basic understanding of Docker and SIEM concepts
- At least 4GB of free memory for the containers

## Lab Architecture

The lab uses the following components:

- **Elasticsearch**: Stores and indexes logs for analysis.
- **Logstash**: Processes and filters incoming logs.
- **Kibana**: Visualizes log data with dashboards.
- **Logs**: Apache server logs as sample input.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/cdanescmd/SIEM-Lab.git
   cd SIEM-Lab

## Default Credentials
- Elasticsearch username: `kibana_system`
- Elasticsearch password: `public-password`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

