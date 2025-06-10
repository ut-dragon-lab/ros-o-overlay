# A ROS-O deb repository for main-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/ut-dragon-lab/ros-o-overlay/blob/main-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/ut-dragon-lab_ros-o-overlay-main-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-ut-dragon-lab_ros-o-overlay-main-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | main-jammy |
| Architecture | amd64 |
| Available Packages | 2 |
| Build Date | Tue Jun 10 02:55:43 UTC 2025 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[fcl_catkin](https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/ros-one-fcl-catkin_0.6.1-11-g1229bd5-2025.06.10.02.42_amd64.deb)" href="#[fcl_catkin](https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/ros-one-fcl-catkin_0.6.1-11-g1229bd5-2025.06.10.02.42_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/fcl_catkin_0.6.1-11-g1229bd5-2025.06.10.02.42-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/ros-one-fcl-catkin_0.6.1-11-g1229bd5-2025.06.10.02.42_amd64-2025-06-10T02:42:15Z.build) | [fcl_catkin](https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/ros-one-fcl-catkin_0.6.1-11-g1229bd5-2025.06.10.02.42_amd64.deb) | 0.6.1-11-g1229bd5-2025.06.10.02.42 | [:books:](https://raw.githubusercontent.com/ut-dragon-lab/ros-o-overlay/main-jammy-one/repository/ros-one-fcl-catkin_0.6.1-11-g1229bd5-2025.06.10.02.42_amd64.files) | [:link:](https://github.com/wxmerkt/fcl_catkin/tree/master) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
