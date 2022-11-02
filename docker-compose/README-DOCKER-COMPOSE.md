# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose up -d`.

## Configured Docker services

### Service registry and configuration server:

- [JHipster Registry](http://localhost:8761)

### Applications and dependencies:

- getaway (gateway application)
- getaway's postgresql database
- invoice (microservice application)
- invoice's mongodb database
- notification (microservice application)
- notification's mongodb database

### Additional Services:

- [Prometheus server](http://localhost:9090)
- [Prometheus Alertmanager](http://localhost:9093)
- [Grafana](http://localhost:3000)