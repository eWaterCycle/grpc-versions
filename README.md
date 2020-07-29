# gRPC for Actions

![Build distro](https://github.com/eWaterCycle/grpc-versions/workflows/Build%20distro/badge.svg)

This repository contains the code and scripts that we use to build gRPC which is accessible through the [setup-grpc](https://github.com/eWaterCycle/setup-grpc) Action.

> Caution: this is prepared for and only permitted for use by setup-grpc action.

## Add new version

1. Adjust grpc version in [.github/workflows/dist.yml](.github/workflows/dist.yml)
2. Create a release with same version
3. Wait for job to add tarballs to release
4. Update versions-manifest.json with new version and tarballs
