# Hi, I'm Samruddhi

I'm a 4th-year engineering student interested in robotics. I've worked on robot arms, mobile robots and a multi-robot team, both in simulation with ROS 2 and on real hardware. Lately I've been training a low-cost robot arm I built to do tasks by learning from my demonstrations.

## Holo Battalion

[![Holo Battalion demo](https://raw.githubusercontent.com/SamruddhiThorat07/eyrc-holo-battalion/main/docs/demo.gif)](https://github.com/SamruddhiThorat07/eyrc-holo-battalion)

For the e-Yantra Robotics Competition 2025-26, our team of four built a system where three holonomic robots sort colour-coded crates into drop zones together. An overhead camera tracks the robots and crates using ArUco markers. Each crate is assigned to a robot, each robot plans its own path with A* while keeping clear of the others, and the commands are sent to the robots over MQTT.

[View the project](https://github.com/SamruddhiThorat07/eyrc-holo-battalion)

## Teaching an SO-101 arm to stack cubes

[![SO-101 cube stacking demo](https://raw.githubusercontent.com/SamruddhiThorat07/so101-act-cube-stacking/main/demo.gif)](https://github.com/SamruddhiThorat07/so101-act-cube-stacking)

I trained an ACT policy in LeRobot on 30 demonstrations so my SO-101 arm could stack three cubes on top of each other. It builds the full tower in 7 out of 10 tries.

[View the project](https://github.com/SamruddhiThorat07/so101-act-cube-stacking)

## SO-101: green cube into a basket

[![SO-101 green cube demo](https://raw.githubusercontent.com/SamruddhiThorat07/so101-act-green-cube/main/docs/demo.gif)](https://github.com/SamruddhiThorat07/so101-act-green-cube)

My first experiment on the same arm. I trained ACT on 10 demonstrations to pick up a green cube and put it in a basket, and it worked 10 out of 10 times.

[View the project](https://github.com/SamruddhiThorat07/so101-act-green-cube)

## Vision-based pick and place with a UR5

[![UR5 pick and place demo](https://raw.githubusercontent.com/SamruddhiThorat07/vision-based-pick-and-place/main/docs/demo.gif)](https://github.com/SamruddhiThorat07/vision-based-pick-and-place)

In Gazebo, a UR5 arm with a depth camera finds objects placed at random on a table, picks them up and drops each one in the bin of its colour. I used Open3D to find the objects in the point cloud and MoveIt 2 to plan the arm's motion. It sorted 28 out of 30 objects correctly.

[View the project](https://github.com/SamruddhiThorat07/vision-based-pick-and-place)

## TurtleBot3 navigation

A TurtleBot3 in Gazebo works out where it is on a map of a house, then drives itself from room to room while avoiding obstacles. I used an EKF and AMCL for localization and Nav2 for navigation.

[View the project](https://github.com/SamruddhiThorat07/turtlebot-nav2)

## Tools I've used

ROS 2, MoveIt 2, Nav2, Gazebo, OpenCV, Open3D, LeRobot, PyTorch, MQTT, ESP32 and Python.

My datasets and trained models are on [Hugging Face](https://huggingface.co/SamruddhiThorat07).
