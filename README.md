# gRPC for Actions

![Build distro](https://github.com/eWaterCycle/grpc-versions/workflows/Build%20distro/badge.svg)

This repository contains the code and scripts that we use to build gRPC which is accessible through the [setup-grpc](https://github.com/eWaterCycle/setup-grpc) Action.

> Caution: this is prepared for and only permitted for use by setup-grpc action.

## Add new version

1. Create a GH release with same version as gRPC version you want to build. For example `v1.30.2`.
1. Wait for GH action job to add tarballs to release
1. Update versions-manifest.json with new version and tarballs
