# xela_server_ros_error

## Issue
When running `roslaunch xela_server_ros service.launch`, the node tries to connect to a WebSocket server at `ws://10.120.0.148:5000` but fails with repeated `[ERROR] Connection refused` messages.

This might be due to the XELA tactile sensor not being connected, powered on, or its server not running.
