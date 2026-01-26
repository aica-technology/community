# Web Video Server

This extension integrates the [Web Video Server](https://github.com/RobotWebTools/web_video_server)
package to the AICA System, making it possible to see ROS 2 image topics for versions of AICA Studio that do not yet
natively support image and video visualizations.

After adding this extension to your AICA System configuration, open a terminal in the running AICA Core and run

```
ros2 run web_video_server web_video_server --ros-args -p port:=8081
```

For more information, refer to
[this](https://github.com/RobotWebTools/web_video_server?tab=readme-ov-file#configuration) section.

## Add to AICA System configuration

If you are using AICA Launcher, add the following Custom Package:

```
ghcr.io/aica-technology/web-video-server:v0.1.0
```

If you are building AICA Core manually with an `aica-application.toml`, add this under `[packages]`:

```
[packages]
# other extensions
"@aica/foss/web-video-server" = "v0.1.0"
```
