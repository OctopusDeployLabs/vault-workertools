# Vault workertools

This repository contains images that contain the tooling necessary to to use the execution container feature with Octopus Deploy when connecting to a HashiCorp vault.

**Note: Please consider this repository provided as is.  If there are any issues please do not contact support.**

## Tags

The following images are built in this repo:

- Ubuntu 22.04 (tagged `latest` in [DockerHub](https://hub.docker.com/r/octopuslabs/vault-workertools/tags?page=1&name=latest))

The version tag corresponds to the version of HashiCorp Vault installed on the image. 
A new image will be built each time a new version of HashiCorp Vault is found.  

The tags are as follows:
- Latest
- [Version] For example `1.13.3`
- Latest-[architecture] For example `latest-ubuntu.2204`
- [Version]-[architecture] For example `1.13.3-ubuntu.2204`

### vault-workertools Tags

Tag | Dockerfile
---------| ---------------
Ubuntu 22.04| [Dockerfile](https://github.com/OctopusDeployLabs/vault-workertools/blob/main/ubuntu-2204/dockerfile)

You can retrieve a list of all available tags for octopuslabs/vault-workertools at https://hub.docker.com/v2/repositories/octopuslabs/vault-workertools/tags.
