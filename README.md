### Dashboard

Dashboard from this project is using from Grafana dashboard https://grafana.com/grafana/dashboards/2587-k6-load-testing-results/

### Verify k6 test with docker from local machine

`docker run --rm -i grafana/k6 run - <scripts/hello-world.js`

### Using docker compose to configure every things

- Start all services `docker-compose up -d`

- Stop all services `docker-compose down`

- Run test and view results throughout Grafana `docker-compose run --rm k6 run /scripts/hello-world.js`
