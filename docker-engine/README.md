![Docker Engine Logo](/images/docker-engine-logo.png)

# Docker Engine

The package for automatic installation of Docker Engine (CE) as a standalone node or a swarm member.

## Requirements

Before installing the package, please consider the following points:
* The appropriate Platform should run Jelastic of [5.2 version or later](https://jelastic.cloud/?versions=5.3_5.2) with the Native Dockers support enabled (i.e. it should contain an [environment region](https://docs.jelastic.com/environment-regions) with [Virtuozzo 7](https://virtuozzo.com/products/virtuozzo/) virtualization being integrated - the appropriate hardware set name(s) could be found within the dedicated column of the [Jelastic Hosting Providers](https://docs.jelastic.com/jelastic-hoster-info) list).
* In order to be successfully installed, the Docker Engine requires a [public SSH key](https://docs.jelastic.com/ssh-add-key) being added to your Jelastic account (whilst the corresponding private key should be handled at your local machine).
* The included option of [Public IP](http://docs.jelastic.com/public-ipv4) attachment is usually provided for billing users only, thus you’ll need to convert your account beforehand.


# References
* [jelastic-jps/docker-native](https://github.com/jelastic-jps/docker-native)
