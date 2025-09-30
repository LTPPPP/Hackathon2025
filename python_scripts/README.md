# Python Scripts

This folder contains all standalone Python scripts for the JetBot project.

## Contents

- **Robot Control Scripts:**

  - `simple_rule_based_robot.py` - Basic rule-based robot behavior
  - `simple_rule_based_robot_main.py` - Main entry point for rule-based robot
  - `map_navigator.py` - Map navigation functionality

- **Line Following Scripts:**

  - `line_following_cv.py` - Computer vision-based line following
  - `line_following_simple.py` - Simple line following implementation
  - `follow_line.py` - Line following functionality

- **LIDAR-based Scripts:**

  - `ros_lidar_collision_avoidance.py` - LIDAR collision avoidance
  - `ros_lidar_follower.py` - LIDAR-based following
  - `ros_lidar_follower_fixed.py` - Fixed version of LIDAR follower
  - `jetbot_lidar_collision_avoidance.py` - JetBot-specific LIDAR collision avoidance

- **Detection & Navigation:**

  - `opposite_detector.py` - Opposite direction detection
  - `caculator.py` - Calculator utilities
  - `check_lidar_follower_deps.py` - Dependency checker for LIDAR follower

- **Setup & Utilities:**
  - `install_dependencies.py` - Install required dependencies
  - `setup_jetbot_lidar.py` - Setup LIDAR for JetBot
  - `mock_camera_publisher.py` - Mock camera publisher for testing
  - `mock_yolo.py` - Mock YOLO detector for testing

## Usage

Most scripts can be run directly from this directory. Make sure to run them from the project root directory so they can access the `jetbot` module and configuration files.
