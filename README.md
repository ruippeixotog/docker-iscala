# ruippeixotog/iscala Docker image

This repository contains the Dockerfile for `ruippeixotog/iscala`, a Docker image containing an [iPython notebook](http://ipython.org/notebook.html) with a [Scala backend](https://github.com/mattpap/IScala).

## How to run

Create a container from this image with:

```
docker run -d -p 8888:8888 ruippeixotog/iscala
```

## Ports

* **8888** - The iPython notebook web interface.

## Volumes

* **/notebooks** - The working directory of the iPython notebook, where notebook files can be placed.
