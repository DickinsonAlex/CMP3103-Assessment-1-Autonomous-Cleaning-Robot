# 🤖 Autonomous Cleaning Robot – "TidyBot" Project

<!-- tags:start -->
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![ROS 2](https://img.shields.io/badge/ROS%202-22314E?logo=ros&logoColor=white) ![Robotics](https://img.shields.io/badge/Robotics-2F6F8F) ![Autonomous Navigation](https://img.shields.io/badge/Autonomous%20Navigation-2F6F8F) ![University of Lincoln: CMP3103 Autonomous Mobile Robotics](https://img.shields.io/badge/University%20of%20Lincoln-CMP3103%20Autonomous%20Mobile%20Robotics-8A1538)
<!-- tags:end -->

This project contains scripts to autonomously control a cleaning robot named TidyBot, built using Python and ROS 2. TidyBot operates in a simulated environment, where it detects, sorts, and organizes colored cubes by matching them to color-coded markers and pushing them into position using camera and LiDAR data.

✅ Core Features:
- DevContainer-enabled ROS 2 workspace for seamless development and simulation
- Main control script for real-time navigation and object interaction
- Multi-sensor fusion using camera and LiDAR
- Collision avoidance and path planning
- Task scheduling and automated return-to-base behavior

🧠 Enhancements:
- Live Debugging UI: Visual map of the bot’s environment, object positions, and movement history
- Simulation Tools: Scripts included for launching the simulation and testing new tasks

🧪 Technical Skills:
Python • ROS 2 • LiDAR • Computer Vision • Autonomous Robotics • DevContainers

https://github.com/user-attachments/assets/20ce27cd-8251-4aa2-90ab-2261e6bf803e

### Development Environment Setup

1. **Container Setup:**
   Once reopened in the container, VSCode will initiate the building process and pull all necessary dependencies. You can monitor the building log within VSCode. This may take a while (in particular if you have not previouly used the computer with the container), as you entire image with all installations is being pulled.
   
   <img width="485" alt="image" src="https://github.com/user-attachments/assets/c3b8202c-dc8e-4f04-a80d-09bc1719a7d0">


2. **Verify Container Environment:**
   After the build completes, VSCode will connect to the container. You can verify that you are within the container environment.

   <img width="1746" alt="image" src="https://github.com/user-attachments/assets/47f9f505-d913-4b2c-a805-3d3ef0809751">
   
   See bottom left, saying "Dev Container":
   <img width="311" alt="image" src="https://github.com/user-attachments/assets/04662426-e7ff-4a00-9838-14e125767895">

   You can now open the virtual desktop (see next section) or a terminal in VSCode inside the DevContainer:
   
   <img width="1158" alt="image" src="https://github.com/user-attachments/assets/088b150f-5cb7-4c0d-b18a-448944f15ffa">


### Devcontainer Features

The devcontainer includes a virtual 3D accelerated (if the host has an NVIDIA GPU and docker runtime installed) desktop.

1. **Accessing the Desktop Interface:**
   Open the user interface by navigating to the `PORTS` tab in VSCode, selected the URL labeled `desktop` to open it in your browser. You can also right-click on the URL it and choose "Preview in Editor" to have that desktop shown directly in VSCode, instead.

   <img width="934" alt="image" src="https://github.com/user-attachments/assets/d90e90ed-3d46-465a-8589-0f96fee5cff2">

2. **Complete the connection:**
   Click on "Connect".

   <img width="404" alt="image" src="https://github.com/user-attachments/assets/33a370cb-6063-4242-ba34-c4997050dcae">

   Your desktop will open. If you want the size of this virtual desktop to adjust automatically to your browser window, choose "Remote Resizing" in the options on the left hand side.

   <img width="276" alt="image" src="https://github.com/user-attachments/assets/d455cb56-4eda-400d-bef2-bf1aa2ef1ca0">

### References

1. [cmp3103-ws](https://github.com/UoL-SoCS/cmp3103-ws)
2. [Get Started with Dev Containers in VS Code](https://youtu.be/b1RavPr_878?si=ADepc_VocOHTXP55)
