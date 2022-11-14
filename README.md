# java-web-maven-spring-jsp-cockroachdb-multi-node-without-ssl-simple

## Description
A jsp springboot java maven build,
that connects to cockroach database

A java sbt build, that connects to 3 node cluster
cockroach database without ssl.

## Tech stack
- springboot
  - jsp
- maven
  - postgres drivers
  - lombok
- bootstrap
- jquery
- dataTable

## Docker stack
- cockroachdb/cockroach:v19.2.2
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
