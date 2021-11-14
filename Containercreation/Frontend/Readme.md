# Frontend

## Build

run the following:
```
CGO_ENABLED=0 && go build .
```

## create container 
run the following (replace "theof75" with your repository):
```
docker build -t theog75/drillfrontend:v1
```


## Running the container

The Backend container requires 2 environment variable named
```
PORT
BACKENDURL
```