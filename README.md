# go-hello 

Simple Hello Word in Golang using buffalo framework and docker to create an image.



## Run
```
buffalo dev
```

## Build Docker

```
docker build -t yourLogin/buffalo-hello:latest . 
```

## Run Docker
```
docker run -p 3000:3000 yourLogin/buffalo-hello
```

## Push to Docker Hub
```
docker login

docker push yourLogin/buffalo-hello:latest