# marv

1. Create `marv.urdf` in `urdf/` directory.
2. Add urdf files to `data_files` in `setup.py`.

Tips and things to remember:

- When using MoveIt Setup Assistant, make sure description package is sourced before running `ros2 launch moveit_setup_assistant setup_assistant.launch.py`

helpful workflows:

- Convert xacro to URDF:

```bash
cd src/marv_description/urdf
ros2 run xacro xacro marv.xacro > marv.xacro.urdf
```