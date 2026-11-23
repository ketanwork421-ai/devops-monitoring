# Node Exporter

Node Exporter collects hardware and operating system metrics from Linux systems.

## Purpose

It exposes system metrics in Prometheus format so Prometheus can scrape and store them.

## Important Metrics

- `node_cpu_seconds_total` - CPU time spent in different modes.
- `node_memory_MemTotal_bytes` - Total system memory.
- `node_memory_MemAvailable_bytes` - Available system memory.
- `node_filesystem_size_bytes` - Total filesystem size.
- `node_network_receive_bytes_total` - Total network data received.

## Access Metrics

Open the following URL when Node Exporter is running:

http://localhost:9101/metrics
