# PoC Monitoring - Prometheus / Grafana

## Config Grafana

> You have to add the prometheus datasource (TODO: find a way to automate it)
> Oauth2 config https://grafana.com/docs/grafana/latest/auth/google/

## Cloudwatch exporter config

> You have to create an IAM role, so the cloudwatch exporter can get metrics from cloudwatch

- https://github.com/prometheus/cloudwatch_exporter
- https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/monitoring-cloudwatch.html
