# Atlas 1.4.5 setup for dev environment
### Get it from dockerhub
```
docker run --restart=always --name=atlas -d -p 7101:7101 eldersoss/atlas
```

### Building the docker image
Clone the repository and execute
```
docker build -t atlas .
```

### Running the container
```
docker run --restart=always --name=atlas -d -p 7101:7101 atlas
```
