# DockerApp-1.0

# Intro 

The Docker App gives you visibility of your Docker Containers, the processes running in them and their resource utilization. Use the DockerApp to get operational visibility of multple docker containers running on the same host. 

## Downloads 

 * [DockerApp-1.1.zip](https://github.com/logscape/DockerApp/raw/master/dist/Docker-1.1.zip)
 * [DockerApp-1.1-override.properties](https://github.com/logscape/dockerapp/raw/master/DockerApp-1.1-override.properties) 

## Configure 

You can run the DockerApp on the same host as your Docker host by using a resource selector. This query 

	bundle.defaults.resourceSelection=hostName containsAny DockerHost 

will select all Forwarders which have the DockerHost substring in them and execute the DockerApp.


## Home

The Home Workspace displays overall container resource utilisation, cpu,memory and network utilisation are display as line charts. 

 ![](docs/images/dockerapp-home.png)

## Processes Metrics 

The Processes Workspace displays the Network, Memory and CPU utilization for all your Docker containers. Clicking on a process id will filter the Workspace to display just that process. 

 ![](docs/images/dockerapp-processes.png)


## Resource
The Resources Workspace provides a container wide view of cpu,memory and network utilisation. 

 ![](docs/images/dockerapp-resources.png)


## Containers 

The Containers Workspaces gives a view of process activity in running containers. 

 ![](docs/images/dockerapp-containers.png)

