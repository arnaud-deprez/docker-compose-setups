#Some docker-compose setups

##Intro

Why I do this project ? Because most of time when you want to test an application,
you can find a docker image but to setup a whole environment, you have to do it
on your own.

With docker-compose, you should be able to setup a complete environment without
effort. So when I spend time to find a docker-compose setup or to build one, I
share it with you.

##Requirements

Some environment are using docker-compose v1 and some are using docker-compose v2.
Each environment has been tested with docker-compose >= 1.6 and docker >= 1.10.

##Environments

* [Docker registry](./docker-registry/README.md)
* [Kafka](https://github.com/wurstmeister/kafka-docker)
* [Kubernetes](https://github.com/vyshane/docker-compose-kubernetes) running on docker
* [Odoo](./odoo/README.md)(formerly known as OpenERP)

##Usage

You can use these setups as is, modify them, or use [docker-compose extend](https://docs.docker.com/compose/extends/#extending-services)
to adapt them to your needs.

##Contributions

Contributions are welcome, feel free to fill pull requests.
