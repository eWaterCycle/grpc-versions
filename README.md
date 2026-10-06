# gRPC for Actions

[![Generate gRPC version](https://github.com/eWaterCycle/grpc-versions/actions/workflows/generate-version.yml/badge.svg)](https://github.com/eWaterCycle/grpc-versions/actions/workflows/generate-version.yml)

This repository contains the code and scripts that we use to build gRPC which is accessible through the [setup-grpc](https://github.com/eWaterCycle/setup-grpc) Action.

> Caution: this is prepared for and only permitted for use by setup-grpc action.

## Add new version

1. Start a [build workflow](https://github.com/eWaterCycle/grpc-versions/actions/workflows/generate-version.yml), set version to for example `1.35.0`. Will create a release with compiled grpc
1. Start a [manifest update workflow](https://github.com/eWaterCycle/grpc-versions/actions/workflows/create-pr.yml) to get updated `versions-manifest.json` file
1. Merge the generated PR
