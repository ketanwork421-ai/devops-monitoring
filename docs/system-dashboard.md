# Grafana System Overview Dashboard

The System Overview dashboard visualizes system performance metrics collected by Prometheus.

## Dashboard Panels

1. CPU Usage (%) - Shows CPU utilization.
2. Memory Usage (%) - Shows memory utilization.
3. Ubuntu Disk Usage (%) - Shows root filesystem usage.
4. Network Traffic - Shows incoming and outgoing traffic in bytes per second.
5. System Uptime - Shows time since system boot.
6. Targets Status - Shows Prometheus scrape target health.
7. Memory Used (GB) - Shows memory currently used.
8. Memory Total (GB) - Shows total system memory.

## Refresh Interval

The dashboard refreshes every 15 seconds.

## Thresholds

- Green: Below 70%
- Orange: 70% and above
- Red: 90% and above

## Dashboard Location

grafana/dashboards/system-overview.json
