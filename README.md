# Self-Balancing Project : FRA501 Robotics DevOps
This project is part of the FRA501 Robotics DevOps course of third-year students at the Institute of Field Robotics (FIBO) to simulate the work system of a **Self-Balancing Robot** with 2 reaction wheels on Gazebo program with ROS2. Our Team includes:
1) Monsicha Sopitlaptana
2) Peerawat Santifuengkul

## **Objective**
1) To simulate the work system of a **Self-Balancing Robot** with 2 reaction wheels on Gazebo program with ROS2.
2) เพื่อเรียนรู้วิธีการ Simulate Environment ที่ใช้ในการทำ Simulation การทำงานของหุ่นยนต์

## **System Architecture**


## **Installation**
Step 1: Clone the repository to the src directory of your workspace.
```
git clone
```

Step 2: Go to the src directory and copy the "self_balancing" package to your src directory in your workspace.

Step 3: Build "self_balancing" in your workspace.
```
cd ~/[your_workspace]
colcon build 
source install/setup.bash
```
## Testing out self_balancing
Terminal1: run launch file

```
cd ~/[your_workspace]
ros2 launch self_balancing sb_robot_spawn_launch.py
```
