# Introduction to Linux and ROS

## What you’ll learn:

- Linux and ROS installation
- Basic Linux commands
- Basics of ROS (publishers and subscribers)

## Prerequisite Software:

The following software is required for the completion of all tasks henceforth:

1. **Ubuntu Linux \- Jammy Jellyfish (22.04)**

   You can:

   - dual boot onto the same drive that has your current OS,
   - use an external SSD/HDD
   - use a Virtual Machine (VM)
   - use WSL

   The last two options are not recommended as the simulation software you'll need to run may be too slow.

   You are also free to use any of the ubuntu derivatives (with the same LTS version) or any other linux distro
   if you know what you're doing and are confident that you can get ROS working reliably.

1. **ROS 2 Humble**

   You can install it using the instructions [here](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html).

   **Make sure you install the `ros-humble-desktop-full` metapackage and not just `ros-humble-desktop`.**

## Task

### Getting familiar with ROS2:

The objective of this task is for you to understand what ROS is and to get you familiar with the tools that are often used in ROS.

Initially, try to get a big picture view of ROS and how it could be helpful in robotics systems.
Reading through the resources should give you a fair idea about what you'll be dealing with.
There are some introductory videos on youtube that you can look up that may help you understand the core concepts of ROS like **Nodes** and **Topics**.
Once you've grasped those, you will be able to better appreciate what you are doing when you follow the tutorials.

## Deliverables

1. Screenshot of your linux desktop with two terminals running the talker and listener node respectively.

## Resources

When learning ROS, the official tutorials for [tools](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools.html)
and [client libraries](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries.html)
are your friends. Although it is recommended to go through all the beginner tutorials on the official page,
make sure you at least read and understand:

1. [Configuring environment](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Configuring-ROS2-Environment.html)
1. [Using turtlesim, ros2, and rqt](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Introducing-Turtlesim/Introducing-Turtlesim.html)
1. [Understanding Nodes](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Nodes/Understanding-ROS2-Nodes.html)
1. [Understanding Services](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Topics/Understanding-ROS2-Topics.html)
1. [Using `colcon` to build packages](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Colcon-Tutorial.html)
1. [Creating a Workspace](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
1. [Creating a Package](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html)
1. [Writing a simple Publisher and Subscriber in C++](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Cpp-Publisher-And-Subscriber.html)
1. [Writing a simple Publisher and Subscriber in Python](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html)

The <u>Concepts and Fundamentals</u> section of the [ROS2 Workshop](https://ros2-industrial-workshop.readthedocs.io/en/latest/index.html) may be helpful too. Just be mindful of the differences that may arise due to it being made for foxy rather than humble.

Remember - you don’t have to complete these in one sitting\! You can go back and forth between the tutorials and the tasks as and when required and take your time trying each of them out making sure you spend the time to read through the material and try to understand the core concept in question.
