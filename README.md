# grafana-prometheus
Simple demo to spin up grafana and prometheus server using docker compose

- Run with `docker compose up`
- Access prometheus server via localhost:9090 
- Access grafana server via localhost:3000
- Add prometheus as a datasource using http://host.docker.internal:9090
- Verify windows exporter running via http://localhost:9182/metrics

