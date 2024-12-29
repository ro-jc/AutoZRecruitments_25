# Controlling Turtlesim

## What you’ll learn:

- Writing a simple publisher and subscriber with custom functionality

## Task

### Turtlesim Circle

The objective of the task is to move the turtle inside the Turtlesim window in a circle and stop at its initial location.

You can achieve this by looking into the topic `/cmd_vel` and controlling linear and angular velocity to complete this task.
You are free to use Python or C++ for the node that you write.

Think about how you can track how much distance the turtle has moved or find some way to get the position of the turtle so that you can make it stop once it has completed a circle.

### Bonus: Turtlesim Sine Wave

The second objective, if you're up for a challenge, is to move the turtle in a sine wave.

We ideally want to see you accomplish this without using any services that the turtlesim package offers (it can technically teleport).

#### Hint (only if you're stuck):

After you know where all in the window you need your turtle to go, one of the links on [this](https://wiki.ros.org/turtlesim/Tutorials) page tells you how to get there.

## Deliverables

1. The ROS package that contains your node (only the particular folder within the `src/` directory in your workspace)
1. A short, simple screencast that shows your turtle running in a circle and stopping. A video shot externally works too
   if you have trouble with screen recording ([OBS](https://obsproject.com/) may help: `sudo apt install obs-studio`).

## Resources

1. [Understanding ROS 2 with Turtlesim](https://ros2-industrial-workshop.readthedocs.io/en/latest/_source/basics/ROS2-Turtlesim.html)
1. [Using turtlesim, ros2, and rqt](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Introducing-Turtlesim/Introducing-Turtlesim.html)
