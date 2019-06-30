Cloud9 v3 with Anaconda Python 3Dockerfile
=============

This repository is based on work by kdelfour.

It extends his original image to contain an up-to-date installation of Anaconda and Python 3.

## Usage

```
docker run -v $(pwd):/workspace -p 8888:80 tophcito/cloud9-docker
```

## Build

To build it, get a recent Anaconda installer from <https://www.anaconda.com/download/>
C.f. <https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart>

```
sudo docker build --tag toph/cloud9-docker:latest
```


