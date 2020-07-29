# gRPC for Actions

![Build distro](https://github.com/eWaterCycle/grpc-versions/workflows/Build%20distro/badge.svg)

This repository contains the code and scripts that we use to build gRPC which is accessible through the [setup-grpc](https://github.com/eWaterCycle/setup-grpc) Action.

> Caution: this is prepared for and only permitted for use by setup-grpc action.

## Add new version

1. Adjust grpc version in [.github/workflows/dist.yml](.github/workflows/dist.yml)
2. Commit & push to trigger GH Action Job
3. Download artifacts from job
4. Create a release with right version
5. Update versions-manifest.json
