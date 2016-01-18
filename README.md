# docker-storm-supervisor


Run Worker with

```
docker run -d --link zookeeper:zookeeper --link nimbus:nimbus --restart always --name worker0 karanamsubbarao/docker-storm-supervisor
```

*Note*: Please replace worker0 with subsequent numbers
