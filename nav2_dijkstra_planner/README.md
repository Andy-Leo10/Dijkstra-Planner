# Dijkstra Planner Plugin

Switch to the branch with Dijkstra Planner

    cd ~/ros2_ws/src/path_planning_checkpoint
    git switch project-work

Terminal 1

    export GAZEBO_MODEL_PATH=/home/user/ros2_ws/src/neobotix_ros2/neo_simulation2/models:/home/user/ros2_ws/src:/home/user/ros2_ws/src/neobotix_ros2
    ros2 launch neo_simulation2 simulation.launch.py

Terminal 2

    ros2 launch neo_nav2 neo_nav2_full.launch.xml