# Icinga 2 + InfluxDB + Grafana Monitoring Dashboards (In Progress)

A simple infrastructure monitoring project using **Icinga 2**, **InfluxDB**, and **Grafana**.

The project focuses on visualizing monitoring data and providing a clear overview of infrastructure and server status through custom Grafana dashboards.

## Architecture

```text
Icinga 2
   │
   ▼
InfluxDB
   │
   ▼
Grafana
   │
   ▼
Monitoring Dashboards
```

## Dashboards

### Infrastructure Overview

Provides a general overview of the monitored infrastructure, including host and service status.

![Infrastructure Overview](screenshots/infrastructure-overview.png)

### Server Monitoring

Provides monitoring information for individual servers and their resources.

![Server Monitoring](screenshots/server-monitoring.png)

## Technologies

* **Icinga 2** – Infrastructure and service monitoring
* **InfluxDB** – Time-series data storage
* **Grafana** – Data visualization and dashboards
* **Linux** – Monitoring environment

## Queries

The Grafana dashboards use queries against the InfluxDB data collected from Icinga 2.

Example queries and panel configurations will be documented in the `queries/` directory.

## Datasource

The Grafana datasource configuration will be documented separately.

> Configuration details containing credentials, internal addresses, hostnames or other sensitive information are intentionally excluded.

## Purpose

This repository is intended as a **technical portfolio project** demonstrating practical experience with infrastructure monitoring, time-series data and Grafana dashboard development.

## Disclaimer

The screenshots and monitoring data have been **anonymized or modified** for demonstration purposes.

No production credentials, sensitive infrastructure information or confidential company data are included in this repository.

