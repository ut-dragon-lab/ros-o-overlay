# ros-o-overlay

This repository supplements [ros-o-builder](https://github.com/v4hn/ros-o-builder) with fewer distributions, enabling fast build.

## How to use

### 1. Adding this APT repository to your system

For available packages and instructions on how to add this APT repository to your system, please refer to this link:

https://github.com/ut-dragon-lab/ros-o-overlay/blob/main-jammy-one/README.md

### 2. Adding new deb distributions to this APT repository

The source list maintained in this repository is a supplement to https://github.com/v4hn/ros-o-builder, therefore, there should not be duplicate items between [the source list in this repository](sources.repos) and [the source list in the ros-o-builder](https://github.com/v4hn/ros-o-builder/blob/build-for-jammy/sources.repos).

To add new deb distributions to this APT repository, please update the `sources.repos` on the **main** branch. A GitHub action will be triggered automatically after you push your commit. This action will build the sources listed in `sources.repos` and then pushes the resulting `.deb` packages to the `main-jammy-one` branch.
