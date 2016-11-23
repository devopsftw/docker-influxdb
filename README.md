# docker-influxdb

InfluxDB with consul agent 

```
docker run -d \
 -e CONSUL_JOIN="consul1 consul2" \
 -e CONSUL_DC="mydc" \
 -e CONSUL_SERVICE_NAME="influx" \
 devopsftw/influxdb
```

Base image: [influxdb](https://hub.docker.com/_/influxdb/)

Additional available envs:

- CONSUL_JOIN
- CONSUL_DC
- CONSUL_SERVICE_NAME
