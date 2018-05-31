# Docker-Scala

Simple Scala Docker experiment 

### Useful commands:

* Publish locally to container
```bash
$ sbt docker:publishLocal
```

* Run inside container
```bash
$ docker run --rm -p9000:9000 docker-scala-akka:0.1-SNAPSHOT 
```

* Run locally (not really necessary)
```bash
$ sbt run
```
