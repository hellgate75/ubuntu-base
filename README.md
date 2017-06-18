# Ubuntu Base Docker image


Docker Image for Base Ubuntu


Provided Ubuntu docker images:
* [Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - 14.04](https://github.com/hellgate75/ubuntu-base/tree/14.04)
* [Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - 16.04](https://github.com/hellgate75/ubuntu-base/tree/16.04)
* [Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - 16.10](https://github.com/hellgate75/ubuntu-base/tree/16.10)
* [Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - 17.04](https://github.com/hellgate75/ubuntu-base/tree/17.04)
* [Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - 17.10](https://github.com/hellgate75/ubuntu-base/tree/17.10)
* [Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - latest](https://github.com/hellgate75/ubuntu-base) (Ubuntu™ Server® with Oracle™ Java® Runtime Environment 8 - 17.10) 


### Introduction ###

Ubuntu Server brings economic and technical scalability to your datacentre, public or private. Whether you want to deploy an OpenStack cloud, a Hadoop cluster or a 50,000-node render farm, Ubuntu Server delivers the best value scale-out performance available.

See [Ubuntu Web Site](https://www.ubuntu.com/server) and [Ubuntu Docker Hub Registry](https://hub.docker.com/_/ubuntu/)


### Goals ###

Simple Operating Ubuntu Server system with optinal features:
* Oracle JDK 1.8
* Networking packages
* Build packages
* System operational package

*No warranties for production use.*



### Docker Image features ###

No Specific configuration, No command or entry-point, no exposed ports


### Docker Environment Variable ###

No Environment Variables

### Sample command ###

Here a sample command to run Ubuntu bash container:

```bash
docker run --rm hellgate75/ubuntu:latest bash
```


### License ###

[LGPL 3](/LICENSE)
