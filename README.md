
---

# Obstacle Avoidance with Depth Camera for Robot

This project implements obstacle avoidance using a depth camera for a robot. The robot uses Python programming language and a depth camera to detect objects in its surroundings and make decisions based on the depth information.

## Overview

The goal of this project is to enable a robot to navigate its environment while avoiding obstacles. The depth camera provides depth information about the objects in front of the robot. The image captured by the depth camera is divided into a 3x3 matrix. By analyzing the final column of the matrix, the robot determines if there are any objects close to it.

If an object is detected in the final column, the robot will make a move to the left to avoid the obstacle. Conversely, if no object is detected in the final column, the robot will make a move to the right. This simple but effective approach allows the robot to maneuver around obstacles and continue its path safely.

## Features

- Obstacle detection using a depth camera
- Matrix splitting of the captured image
- Left or right movement decision based on the presence of obstacles
- Integration with Python programming language
- Easy-to-understand and extendable codebase

## Requirements

- Python 3
- Depth camera

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/balaji-89/obstacle_avoidance.git
   ```

2. Connect the depth camera to your robot and ensure it is properly configured.

3. Run it cell by cell:

   The script will capture images from the depth camera, split them into a 3x3 matrix, analyze the final column, and instruct the robot to move left or right accordingly.

4. Watch as your robot navigates its environment while avoiding obstacles!

Feel free to modify and adapt the content according to your project's specific details and requirements.
