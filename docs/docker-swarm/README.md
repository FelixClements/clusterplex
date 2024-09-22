![docker-swarm](../images/docker-swarm-logo-small.png)


## Examples for Docker Swarm

Here you can find examples for deploying cluster-plex with hw transcodeing using docker-swarm. 
* First deploy the device-manager stack as this is needed to give the plex stack access to the GPU -> [device-manager.yml](device-manager.yml)
* It is not requewent to deploy the network stack but i have it to make my life easyer -> [network.yml](network.yml)
* Deploy the plex cluster with this yml [Cluster-Plex.yml](Cluster-Plex.yml)
