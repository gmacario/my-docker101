my-docker101
============

Based on the "Docker 101" presentation by [Andrea Tosatto](https://www.linkedin.com/in/atosatto) at the [GDG Talk Meeting](http://it.droidcon.com/2016/talk-meeting-talent-garden-torino/) c/o Talent Garden, Torino, 2015-07-09.

Original sources available at <https://github.com/hilbert-/presentation-docker101>

Original Docker image available at <https://registry.hub.docker.com/u/hilbert/docker101/>

Displaying original Docker 101 slides
-------------------------------------

Source available at <https://github.com/hilbert-/presentation-docker101>

```
$ docker pull hilbert/docker101
$ docker run -p 4080:8080 hilbert/docker101
```

then open a web browser to <http://localhost:4080/>

Trying my own Docker image
--------------------------

```
$ docker build -t gmacario/my-docker101 .
$ docker run -p 4180:8080 gmacario/my-docker101
```

then open a web browser to <http://localhost:4180/>

<!-- EOF -->
