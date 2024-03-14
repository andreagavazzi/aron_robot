<img align="right" src="https://github.com/andreagavazzi/ag_perception/blob/main/assets/ag_logo.jpg" alt="ag_logo" width="200"/>  

# Aron
Aron is my variation of the Poppy Humanoid robot. It is a robot torso which is a little bit more affordable than the Poppy Humanoid and therefore it is an ideal medium to learn science, technology, engineering and mathematics.
Like Poppy Humanoid, Aron is an open-source robot (both hardware and software), built with 3D printed parts and Dynamixel servomotors, known for their reliability.
Aron's brain combines the power of the NVIDIA Jetson Orin Nano for vision recognition and image processing, along with the Teensy acting as its limbic system for emotional reactions.

### NVIDIA Jetson Orin Nano (Brain):
Purpose: The Jetson Orin Nano serves as the high-performance cognitive center of Aron's brain.
- **Vision Recognition**: With impressive processing power, Jetson Orin Nano analyzes visual data from cameras, and other sensors. It identifies objects, detects patterns, and recognizes scenes.
- **Image Processing**: Jetson Orin Nano efficiently handles image manipulation tasks such as filtering, edge detection, and feature extraction.
- **Deep Learning**: It runs neural networks for complex tasks like object detection, semantic segmentation, and pose estimation.
- **High-Speed Interfaces**: Jetson Orin Nano supports interfaces like PCIe Gen4, USB 3.1, and Gigabit Ethernet, enabling seamless communication with external devices.  

### Teensy (Limbic System):
Inspired by the human limbic system, the Teensy 4.1 board provides emotional responses.
- **Emotional State Simulation**: The Teensy emulates emotions like joy, fear, curiosity based on input from the Jetson Orin Nano. For example, it might express excitement when recognizing a friendly face.
- **Visual feedback** to routine running in the brain: If Jetson Orin Nano is throwing an error, debug informations are easily visualized.

### Dynamixel Intelligent Motors (Joint Control):
Integration with Joints: Aron's jonts are equipped with Dynamixel intelligent motors. These motors provide precise control to execute physical movements.
- **Position Control**: Dynamixel motors allow fine-grained position control, ensuring accurate joint angles.
- **Feedback Mechanism**: They provide real-time feedback on joint position, temperature, and load.
- **Smart Communication**: Dynamixel motors communicate via UART, enabling seamless coordination with Jetson Orin Nano.
- **Customizable Behavior**: They can be programmed on specific joint behaviors, such as compliant motion or torque limits.  

### Packages
Currently only ROS is supported

| Package name | Description | Notes |
| -------- | ----------- | :-----------: |
| [aron_description](https://github.com/andreagavazzi/aron_description) | This package contains the URDFs and meshes for Aron |  |
| [aron_control](https://github.com/andreagavazzi/aron_control) | This package contains the configurations and launch files |  |
| [aron_ros_control](https://github.com/andreagavazzi/aron_ros_control) | This package provides the ROS controllers for MoveIt  |  |


#  

 <p align="left">
  <img width="300" src="https://github.com/andreagavazzi/aron/blob/main/pics/ros_gazebo.png" alt="ag_logo">
</p>


