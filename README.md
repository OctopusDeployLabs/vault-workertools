# Vault workertools

This repository contains images that contain the tooling necessary to to use the execution container feature with Octopus Deploy when connecting to a HashiCorp vault.

The image is built from the `alpine` platform.

**Note: Please consider this repository provided as is.  If there are any issues please do not contact support.**

## Tags

The version tag corresponds to the version of HashiCorp vault installed on the image. 
A new image will be built each time a new version of Octopus CLI is created.  

The tags are as follows:
- Latest
- [Version] For example `1.13.3`
- Latest-[architecture] For example `latest-alpine`
- [Version]-[architecture] For example `1.13.3-alpine`

### vault-workertools Tags

Tag | Dockerfile
---------| ---------------
alpine| [Dockerfile](https://github.com/OctopusDeployLabs/vault-workertools/blob/main/alpine/dockerfile)

You can retrieve a list of all available tags for octopuslabs/vault-workertools at https://hub.docker.com/v2/repositories/octopuslabs/vault-workertools/tags.
