# ClusterPlex
[![GitHub license](https://img.shields.io/github/license/pabloromeo/clusterplex.svg)](https://github.com/pabloromeo/clusterplex/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/pabloromeo/clusterplex.svg)](https://GitHub.com/pabloromeo/clusterplex/releases/)
[![ci](https://github.com/pabloromeo/clusterplex/actions/workflows/main.yml/badge.svg)](https://github.com/pabloromeo/clusterplex/actions)

## What is it?

ClusterPlex is basically an extended version of [Plex](https://plex.tv), which supports distributed Workers across a cluster to handle transcoding requests.
It has been tested on Kubernetes and Docker Swarm.

![Docker Swarm](docs/images/docker-swarm-logo-small.png)



## Installation

See the [docs](docs/) section for details on each component's configuration parameters and example configurations both on Kubernetes and Docker Swarm.

* [Configuration Parameters](docs/)
* [On Docker Swarm](docs/docker-swarm/)
* [Grafana Dashboard and Metrics](docs/grafana-dashboard/)
