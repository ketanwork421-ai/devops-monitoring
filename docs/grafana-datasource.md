# Grafana Prometheus Datasource

Grafana is used to visualize monitoring data collected by Prometheus.

## Datasource Configuration

Grafana connects to Prometheus using the following URL:

http://prometheus:9090

## Provisioning

The datasource is automatically configured using:

grafana/provisioning/datasources/prometheus.yml

## Configuration Details

- Name: Prometheus
- Type: prometheus
- Access: proxy
- Default datasource: Yes
- Editable: Yes

## Benefits

- Automatically connects Grafana to Prometheus.
- Avoids manual datasource configuration after restarting the stack.
- Allows dashboards to query Prometheus metrics.
