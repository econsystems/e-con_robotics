# e-con Robotics

**e-con Robotics** is the central repository for our research team's robotics projects. This repository serves as a hub for ongoing initiatives, providing documentation, references, and links to individual project repositories. It is structured to provide a professional overview of our research and development activities.

---

## About

We are a research team focused on advanced robotics solutions, including autonomous navigation, perception, and sensor integration. Our projects leverage **ROS 2** and **e-con Systems’ Robotic Computing Platform (RCP)** for development and experimentation.

### Core Competencies

- Autonomous navigation and mapping (single and multi-robot systems)
- Docking and charging station integration
- Robot perception and sensor fusion
- Object tracking and human-following systems
- Low-level obstacle detection using depth and ToF sensors

These projects encompass both software and hardware aspects of robotics, including AI-based perception, motion planning, and integration with custom robotic platforms.

---

## Robotic Computing Platform (RCP)

**eRCP – Robotic Computing Platform (RCP)** is based on the **Ambarella CV72S AI Vision Processor**. The platform provides:

- **CV72S Vision Processor Module (VPM)**  
- Carrier board with multiple interfaces, sensor arrays, and motor control interfaces  
- Full SDK supporting the ROS 2 stack, with pre-implemented navigation and mapping algorithms  
- High customizability to meet specific automation requirements  
- Support for integration of new hardware and software peripherals  

The RCP provides a robust foundation for robotics development, enabling researchers and developers to build advanced robotic applications efficiently.

---

## Projects

### Project 1 – ROS 2 Multi-Robot Autonomous Mapping

- **Repository:** [ros2-multi-robot-autonomous-mapping](https://github.com/econsystems/ros2-multi-robot-automap)  
- **Description:** Multi-robot autonomous mapping and navigation using ROS 2, SLAM Toolbox, and Navigation2. Supports Gazebo simulation, RViz visualization, and deployment on real mobile compatible robots.
- **Blog & Documentation:** 
   - BLOG 1: [why-multi-robot-autonomous-mapping-is-becoming-essential-for-large-scale-facilities-part-1](https://www.e-consystems.com/blog/camera/applications/why-multi-robot-autonomous-mapping-is-becoming-essential-for-large-scale-facilities-part-1/)  
   - BLOG 2: [how-to-overcome-vision-challenges-while-building-a-multi-robot-mapping-system-part-2](https://www.e-consystems.com/blog/camera/applications/how-to-overcome-vision-challenges-while-building-a-multi-robot-mapping-system-part-2)


### Project 2 – ROS 2 Docking System

- **Repository:** [ros2-docking-system](https://github.com/econsystems/ros2-docking)  
- **Description:** Multi-robot docking system for autonomous charging on real mobile robots, featuring a complete ROS 2 package and Yocto-based embedded workflow with Nav2 navigation, ArUco marker detection, and battery-aware mode switching.
- **Blog & Documentation:** 
   - BLOG 1: [how-robot-fleets-achieve-full-mission-autonomy-from-ros-2-autonomous-docking-to-self-charging](https://www.e-consystems.com/blog/camera/technology/how-robot-fleets-achieve-full-mission-autonomy-from-ros-2-autonomous-docking-to-self-charging/)  
   - BLOG 2: [what-are-the-key-engineering-challenges-in-autonomous-docking-systems-and-how-are-they-solved-part-2]([https://www.e-consystems.com/blog/camera/applications/how-to-overcome-vision-challenges-while-building-a-multi-robot-mapping-system-part-2](https://www.e-consystems.com/blog/camera/applications/what-are-the-key-engineering-challenges-in-autonomous-docking-systems-and-how-are-they-solved-part-2/)

### Project 3 – DepthVista Helix Isaac Sim Camera

- **Repository:** [DepthVista-Helix-IsaacSim-Camera](https://github.com/econsystems/DepthVista-Helix-IsaacSim-Camera)
- **Description:** Adds the e-con DepthVista Helix iToF camera to Isaac Sim's supported cameras and depth sensors, with a ROS 2 publisher, a browser-based depth/point-cloud viewer, and ready-to-run example scenes.
- **Blog & Documentation:** 
   - BLOG 1: [robotics-development-just-got-faster-smarter-e-con-systems-itof-3d-camera-comes-to-nvidia-isaac-sim](https://www.e-consystems.com/blog/camera/technology/robotics-development-just-got-faster-smarter-e-con-systems-itof-3d-camera-comes-to-nvidia-isaac-sim/)  
> Additional projects will be added as separate repositories as they are finalized.

---

## Contact & Blog

For updates, discussions, and blog posts related to our robotics projects, visit:  
[https://www.e-consystems.com/blogs/](https://www.e-consystems.com/blog/camera/category/applications/)
