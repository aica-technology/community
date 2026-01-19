# Topic Based ROS 2 Control

This extension integrates the [Topic Based ROS 2 Control](https://github.com/PickNikRobotics/topic_based_ros2_control)
package to the AICA System, making the `topic_based_ros2_control/TopicBasedSystem` hardware interface available for use.
This hardware interface implements a system supporting state and command interfaces through ROS topics to communicate
with external simulators such as Isaac Sim.

To add this in your AICA System configuration, add the following custom extension:

```
"@aica/foss/topic-based-ros2-control" = "v0.1.0"
```
