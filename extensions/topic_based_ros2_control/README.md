# Topic Based ROS 2 Control

This extension integrates the [Topic Based ROS 2 Control](https://github.com/PickNikRobotics/topic_based_ros2_control)
package to the AICA System, making the `topic_based_ros2_control/TopicBasedSystem` hardware interface available for use.
This hardware interface implements a system supporting state and command interfaces through ROS topics to communicate
with external simulators such as Isaac Sim.

## Add to AICA System configuration

If you are using AICA Launcher, add the following Custom Package:

```
ghcr.io/aica-technology/topic-based-ros2-control:v0.1.0
```

If you are building AICA Core manually with an `aica-application.toml`, add this under `[packages]`:

```
[packages]
# other extensions
"@aica/foss/topic-based-ros2-control" = "v0.1.0"
```
