# ClusterPlex (Forked for Docker Swarm, Intel Hardware Transcoding, and Enhanced Monitoring)
[![GitHub license](https://img.shields.io/github/license/pabloromeo/clusterplex.svg)](https://github.com/pabloromeo/clusterplex/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/pabloromeo/clusterplex.svg)](https://GitHub.com/pabloromeo/clusterplex/releases/)
[![ci](https://github.com/pabloromeo/clusterplex/actions/workflows/main.yml/badge.svg)](https://github.com/pabloromeo/clusterplex/actions)

## What is it?

This fork of ClusterPlex is tailored to focus specifically on Docker Swarm, with enhanced support for Intel hardware transcoding and docs and how to deploy a monitoring stack. 

ClusterPlex itself is an extended version of [Plex](https://plex.tv) that allows you to distribute transcoding tasks across a cluster using dedicated Workers. This fork aims to make it easier to leverage Docker Swarm environments, integrate Intel Quick Sync Video (QSV) hardware acceleration for transcoding, and offer built-in monitoring options through Grafana and Prometheus.

![Docker Swarm](docs/images/docker-swarm-logo-small.png)

## Installation

Please refer to the [docs](docs/) section for details on each component, including configuration parameters, and example setups targeted at Docker Swarm along with optimizations for Intel hardware transcoding and monitoring.

* [Configuration Parameters](docs/)
* [On Docker Swarm](docs/docker-swarm/)
* [Grafana Dashboard and Metrics](docs/grafana-dashboard/)
