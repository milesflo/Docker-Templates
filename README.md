![](assets/header.png)

Welcome to TheHive Project's Docker Templates repository.

It's hosting docker configurations for TheHive, Cortex and 3rd party tools integrations.

# What's in it?

This repository aims to be a location where TheHive and Cortex users can find and share docker compose configuration files for

- TheHive
- Cortex
- MISP
- Reverse Proxies
- OAuth Providers
- Workflow and automation tools
- Feeders

## Common configuration

This section describes the possible configuration options for the major components

### How to configure Elasticsearch

```
TODO
```

### How to configure Cassandra

```
TODO
```
### How to configure TheHive

- How to configure TheHive
  - `application.conf` file
  - `logback.xml` file

```
TODO
```
### How to configure Cortex
- How to configure Cortex
  - dockerized neurons
  - local neurons
  - permissions
  - `application.conf` file
  - `logback.xml` file

```
TODO
```

## Available templates

### Basic templates
- [TheHive 3 + Cortex 3](./docker/thehive3-cortex3-es7)
- [Cortex 3 with dockerized neurons](./docker/cortex3-dockerized-neurons)

### Custom templates
- [TheHive 3 + Cortex 3 + ES 6 + Traefik + Route53](./docker/thehive3-cortex3-es6-traefik-route53) by [@aacgood](https://github.com/aacgood) 
- [TheHive 3 + Cortex 3 + ES7 + Traefik + Route53](./docker/thehive3-cortex3-es7-traefik-route53) by [@aacgood](https://github.com/aacgood) 

## TODO

The list bellow includes the docker-compose configurations to be done:

- [ ] TheHive 3 + Elasticsearch
- [ ] TheHive 4 + BerkleyDB
- [ ] TheHive 4 + Cassandra
- [ ] Cortex 3 + dockerized neurons
- [ ] Cortex 3 + local neurons
- [ ] Add reverse proxy
  - [ ] Caddy?
  - [ ] Nginx ?
  - [ ] Traefik ?
- [ ] Add oauth providers
  - [ ] keycloak ?
  - [ ] Fusionauth ?


# Contributing
Please see our [Code of conduct](code_of_conduct.md). We welcome your contributions. Please feel free to fork the code, play with it, make some patches and send us pull requests via [issues](https://github.com/TheHive-Project/TheHive/issues).
