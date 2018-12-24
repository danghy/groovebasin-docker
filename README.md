Docker image for [Groove Basin](https://github.com/andrewrk/groovebasin) music server

# How to use this image

```
$ docker run -p 6600:6600 -p 8333:16242 -v /my/own/musicdir:/home/groovebasin/music -v /my/own/datadir:/home/groovebasin/groovebasin.db --privileged --restart=always --name groovebasin -d hydang/groovebasin-docker
```
