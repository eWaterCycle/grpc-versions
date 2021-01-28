# gRPC for Actions

![Build distro](https://github.com/eWaterCycle/grpc-versions/workflows/Build%20distro/badge.svg)

This repository contains the code and scripts that we use to build gRPC which is accessible through the [setup-grpc](https://github.com/eWaterCycle/setup-grpc) Action.

> Caution: this is prepared for and only permitted for use by setup-grpc action.

## Add new version

1. Start a [build workflow](https://github.com/eWaterCycle/grpc-versions/actions?query=workflow%3A%22Generate+grpc+version%22), set version to for example `1.35.0`. Will create a release with compiled grpc
1. Start a [manifest update workflow](https://github.com/eWaterCycle/grpc-versions/actions?query=workflow%3A%22Create+Pull+Request%22) to get updated `versions-manifest.json` file
1. Merge the generated PR
