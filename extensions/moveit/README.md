# MoveIt Extension

This extension integrates the core stack of [MoveIt 2](https://github.com/moveit/moveit2) to the AICA System, enabling
the use of advanced motion planning and manipulation capabilities. Hardware-specific assets are not provided by this
extension and have to be developed on top (for example, through the
[MoveIt Setup Assistant](https://moveit.picknik.ai/main/doc/examples/setup_assistant/setup_assistant_tutorial.html)).

## Add to AICA System configuration

If you are using AICA Launcher, add the following Custom Package:

```
ghcr.io/aica-technology/moveit:v0.1.0
```

If you are building AICA Core manually with an `aica-application.toml`, add this under `[packages]`:

```
[packages]
# other extensions
"@aica/foss/moveit" = "v0.1.0"
```
