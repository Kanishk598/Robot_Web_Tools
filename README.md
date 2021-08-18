# Robot_Web_Tools
Web-based controller for AR-Drone, made using ROSLIBJS. I can now control the robot using my phone, by opening a webserver on my Ubuntu PC and opening this webpage on phone.

0. Change the robot's IP (line 14 in `robot.html`) to your own robot's/machine running ROS's IP.
1. Start your robot. Example: `roslaunch turtlebot3_gazebo turtlebot3_world.launch`
2. Start a websocket using ROSBridge. `roslaunch rosbridge_server rosbridge_websocket.launch`
3. Connect your robot and webpage in same WiFi network. Example: If your webpage is on the robot itself, make a server on robot using `python -m SimpleHTTPServer` and open the same webpage on another device on the same WiFi network.
4. Start moving your robot using the webpage buttons.

<br><br>
This is the controller, opened in my phone.<br>
<img src="phone.jpeg" class="img-responsive" alt="" width="400" height="200" />
<br>
This is the robot in my PC, being controlled remotely by my phone.<br>
<img src="robot.jpeg" class="img-responsive" alt="" width="900" height="400" />
