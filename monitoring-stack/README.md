
# Monitoring Stack Setup (Prometheus + Grafana)

## Prerequisites
- Docker
- Docker Compose

## Run the Monitoring Stack

```bash
docker compose up -d
```

## Services

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000
  - Username: admin
  - Password: admin

## Validate Metrics

Open:

```bash
http://localhost:5000/metrics
```

You should see Prometheus metrics.

## Stop Services

```bash
docker compose down
```
