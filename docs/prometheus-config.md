# Prometheus Configuration

Prometheus is an open-source monitoring and alerting system.

## Configuration

The configuration file is located at:

prometheus/prometheus.yml

## Scrape Interval

The scrape interval is configured to 15 seconds.

## Monitored Targets

1. Prometheus - localhost:9090
2. Docker Node Exporter - node-exporter:9100
3. Ubuntu Node Exporter - host.docker.internal:9101

## Useful PromQL Queries

Check target status:

up

Check CPU metrics:

node_cpu_seconds_total

Check total memory:

node_memory_MemTotal_bytes
