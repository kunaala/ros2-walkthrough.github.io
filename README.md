# [ros2-walkthrough.github.io](https://ros2-walkthrough.github.io)  
### Getting Started with ROS 2

**ROS 2** (Robot Operating System 2) is an open-source middleware framework designed to simplify and modularize robot software development.

---

## Why ROS 2?

### 1. **Modular Design for Robotics**
- Robot components such as sensors, motor controllers, manipulators, and wheel encoders can each be represented as individual **nodes**.
- The code that defines and manages these nodes can be grouped and distributed as self-contained **ROS 2 packages**.

### 2. **Reliable Node Communication**
ROS 2 provides built-in communication mechanisms that help coordinate how nodes interact:

- **Topics** — For asynchronous, publish-subscribe messaging (similar to MQTT).
- **Services** — For synchronous, request-response interactions (similar to HTTP).
- **Actions** — Like Services, but allow progress feedback while a task is running.

### 3. **Powerful Peer-to-Peer DDS Protocol**
- ROS 2 leverages **DDS (Data Distribution Service)**, a peer-to-peer communication protocol.
- Nodes can discover and connect with each other automatically using DDS's built-in discovery mechanisms.
- Unlike ROS 1, there’s no need for a central master — making the system more scalable and resilient.

**You’ve Already Learned Key ROS 2 Concepts! Hooray!**Im done with this step 🙌
By now, you're familiar with the essential building blocks of ROS 2:

- ✅ **Nodes**  
- ✅ **ROS 2 Packages**  
- ✅ **Topics**  
- ✅ **Services**  
- ✅ **Actions**  
- ✅ **DDS**

---

## Common ROS2 tools
- ROS2 also unlocks access to tools that can help inspect and interact with the robot. Some ROS2 hits that are worth our attention are:

  **1.Rosbags** : Subscribe topics and record data to replay them to emulate the same conditions/results  
  **2.rqt** : Visualize topics to view the robot and its interaction with the environment  
  **3.tf** : Managing transformations between different parts of the robot : key for navigation and SLAM  

---

## A practical example:






