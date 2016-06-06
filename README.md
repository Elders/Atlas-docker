# Atlas 1.4.5 setup for dev environment
### Building the docker image
```
docker build -t atlas docker/
```

### Running the container
```
docker run --restart=always --name=atlas -d -p 7101:7101 atlas
```
