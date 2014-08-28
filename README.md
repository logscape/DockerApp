# DockerApp-1.0

# Intro 

Monitor resources of a  Docker host, its containers, and the processes that each container runs. Identify outliers and create alerts for your docker images and containers. 

## Downloads 

 * [DockerApp-1.0.zip](https://github.com/logscape/dockerapp/raw/master/DockerApp-1.0.zip)
 * [DockerApp-1.0-override.properties](https://github.com/logscape/dockerapp/raw/master/DockerApp-1.0-override.properties) 

## Configure 

The following configuration is optional. Download the DockerApp-1.0-override.properties file and update the resourceSelection query. This query selects

	bundle.defaults.resourceSelection=hostName containsAny WebFarmAgent

which agent the docker app is going to run on. The agent has to run on the same host as docker for the metrics to be collected and visualized. 

## Caches 
 ![](docs/images/dockerapp-home.png)

## Client Requests 
 ![](docs/images/dockerapp-resources.png)

## Processes
 ![](docs/images/dockerapp-processes.png)



