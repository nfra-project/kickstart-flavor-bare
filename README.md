
# kickstart-flavor Bare development container

[![Actions Status](https://github.com/nfra-project/kickstart-flavor-bare/workflows/test/badge.svg)](https://github.com/nfra-project/kickstart-flavor-bare/actions)
[![Docker Pulls](https://img.shields.io/docker/pulls/nfra/kickstart-flavor-bare.svg)](https://github.com/nfra-project/kickstart-flavor-bare)

see (http://github.com/infracamp/kickstart) for more information.

Document Index:

- [Development Guide for this flavor](DEVELOPMENT.md)
- [Dockerhub page](https://hub.docker.com/r/nfra/kickstart-flavor-bare/)
    - [Tags available](https://hub.docker.com/r/nfra/kickstart-flavor-bare/tags/)
    - [Build details](https://hub.docker.com/r/nfra/kickstart-flavor-bare/builds/)


## Tags

*Use -min images in Dockerfile and main image in .kick.yml*

| Tag         | OS                            | Branch     | Docs |
|-------------|-------------------------------|------------|------|
| 1.0         | Ubuntu 20.04                  | 1.0-stable | [Readme](https://github.com/nfra-project/kickstart-flavor-bare/tree/1.0-stable) |
| unstable    | Ubuntu 20.04 (master), PHP8   | master     | [Readme](https://github.com/nfra-project/kickstart-flavor-bare/) |


## Default configuration

You can use the template function to write configuration files on container startup by placing them
into `.kicker/conf/<targetpath>`. These files will be evaled during container startup.

## Installed Software

Make sure your IDE has plugins installed for:

