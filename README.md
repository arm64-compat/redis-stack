# Redis Stack ARM64 Compatible Image

[![Build Status](https://app.travis-ci.com/arm64-compat/redis-stack.svg?branch=main)](https://app.travis-ci.com/arm64-compat/redis-stack)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The submodules being used here are liscenced under [Redis Source Available License](https://github.com/RediSearch/RediSearch/blob/master/LICENSE) (RSAL).

This repository provides `linux/amd64` & `linux/arm64` compatible images for [Redis Stack Server](https://redis.io/docs/stack/).

Images are natively built and not using QEMU emulation support thus are faster when used with compatible CPU architecture.

**Note**: images are only for development purposes and has not been tested for production ready use-cases.

As Mac M1 chip processor laptops are becoming increasily popular, running incompatible containers are slower and impacts productive. Enumlated images are resource hungry and doesn't let you leverage the benefits of M1 Chip.

## Supported Images & Tags

Since these images are meant to be only used for development purposes, vast variety of support for different flavors is not provided. However if there is enough interests, contributions are welcome.

You can refer to [GHCR Package Repository](https://github.com/orgs/arm64-compat/packages?repo_name=redis-stack) for a list of available packages, versions and tags.

### Base Image

`redisfab/redis` base image is used with `bullseye` flavour.
