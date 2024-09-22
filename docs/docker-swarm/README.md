![docker-swarm](../images/docker-swarm-logo-small.png)

Examples for Docker Swarm
Here you will find examples for deploying Cluster-Plex with hardware transcoding using Docker Swarm.

Important:
You will need to modify the provided .yml files to suit your own environment and configuration. These files might contain specifics such as network configurations, volume paths, or GPU identifiers that will need to be customized to match your hardware and network setup. Make sure to review and adapt them accordingly for your deployment.

Steps for Deployment:
Deploy the Device-Manager Stack

This is required to grant the Plex stack access to the GPU for hardware transcoding.

File: [device-manager.yml](device-manager.yml)

(Optional) Deploy the Network Stack

While it is not mandatory, deploying the network stack can simplify your setup by managing network configurations. I use this in my setup for convenience.

File: [network.yml](network.yml)

Deploy the Plex Cluster

After preparing the device manager (and optionally the network stack), you can deploy the Plex cluster using the following file.

File: [Cluster-Plex.yml](Cluster-Plex.yml)
