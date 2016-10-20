# docker-influxdb

InfluxDB with consul agent 

```
docker run --rm -e CONSUL_HOST=consul devopsftw/influxdb:latest influxd 
```

Base image: [influxdb](https://hub.docker.com/_/influxdb/)

Additional available envs:

- CONSUL_HOST
- CONSUL_DC
- CONSUL_DOMAIN
- CONSUL_SERVICE_NAME