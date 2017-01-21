# dork.db
## Getting Started

* Download docker for [Windows](https://docs.docker.com/docker-for-windows/) or [Linux](https://docs.docker.com/engine/installation/linux/ubuntu/) on the official docker site and follow the installation instructions
* Request collaborator access for the official Docker Hub repository [xpitfire/dork.db](https://hub.docker.com/r/xpitfire/dork.db) via slack if not already available
* Run a terminal or PowerShell instance and execute the following command: 
```
docker run -p 27017:27017 --name dorkdb -d xpitfire/dork.db
```

* To start the docker container execute:
```
docker start dorkdb
```

* You can now use the following connection string for local hosting: 
```
mongodb://localhost:27017/local
```
