# FSO_Lab

![Under Construction](https://media.tenor.com/MRCIli40TYoAAAAj/under-construction90s-90s.gif)
![Under Construction](https://media.tenor.com/MRCIli40TYoAAAAj/under-construction90s-90s.gif)
![Under Construction](https://media.tenor.com/MRCIli40TYoAAAAj/under-construction90s-90s.gif)
![Under Construction](https://media.tenor.com/MRCIli40TYoAAAAj/under-construction90s-90s.gif)

Welcome to the Full Stack Observability Home Lab (FSO_Lab)! This repository is designed to help you learn and practice full stack observability concepts.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Workflow](#workflow)


## Introduction

FSO_Lab is a home lab environment that provides hands-on experience with full stack observability. It includes tools and techniques for monitoring, logging, and tracing across the entire stack, from frontend to backend.

## Features

- **Monitoring**: Track the performance and health of your applications.
- **Logging**: Collect and analyze logs from various components.
- **Tracing**: Trace requests across services to diagnose issues.
- **Dashboards**: Visualize metrics and logs in real-time.

## Getting Started

Follow these instructions to set up and run the FSO_Lab on your local machine.

## Prerequisites

- Git
- Ansible


## Usage

Once the lab environment is up and running, you can access the various observability tools through the provided URLs. Refer to the documentation for each tool to learn how to use them effectively.

## Contributing

Contributions are welcome! Please read the CONTRIBUTING.md file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Workflow

All changes will be made via Git. There is a self-hosted runner on the Nuc that pulls changes and will run an Ansible playbook to deploy the updates. The Nuc acts as the bastion host, running Grafana and InfluxDB, and deploying the Ansible roles for Grafana, Telegraf, Prometheus, and InfluxDB.