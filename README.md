# Ant 1.7 and jdk 1.6 image

[Docker](https://www.docker.io/) image for compiling with [ant](https://ant.apache.org) 1.7 and jdk 1.6.

This is an image used strictly for *legacy* compilations.

**DO NOT USE IN NEW PROJECTS!!!**

Sample docker invokation:

```sh
$ docker run --rm -it -v /local-source-dir:/source \
                      agusmba/ant -version
```

Other similar projects:

* [frekele/ant](https://github.com/frekele/docker-ant) from which this project borrows heavily.