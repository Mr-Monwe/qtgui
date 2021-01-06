# Veronica's GUI

The main competition GUI interface for Veronica. It contains all competition modes and is written using **[PyQt5](https://doc.qt.io/qtforpython/#documentation)**.

All modes are stored as a list in a combobox and all the logic is stored in the change_dropdown function. 

_For the **full high level overview** of each mode, go to the **[wiki](https://github.com/waynerobotics/veronica/wiki/Software)**._

<p>&nbsp;</p> 

| Mode                 | Description                                |
| -------------------- | ------------------------------------------ |
| Main Competition     | Launch robot on competition track          |
| Lane Mode            | Test lane following                        |
| Speed Mode           | Test the robot's average speed             |
| Obstacle Mode        | Test obstacle avoidance                    |
| Waypoint Mode        | Test waypoint following                    |
| Init Param Server    | Initialize veronica's parameter server     |
| Status Check         | Check the health status of the robot       |
| Kill All             | Kill all active nodes & shutdown the robot |

<p>&nbsp;</p>

![Screengrab](screengrab.png)
