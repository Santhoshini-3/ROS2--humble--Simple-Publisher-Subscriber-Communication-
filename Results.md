The figure depicts terminal outputs from the ROS2 system where a publisher node (left) sends incremented messages ("Robot is running: X") every 0.1 seconds, 
and a subscriber node (right) logs these messages as they are received, demonstrating real-time inter-node communication using ROS2. 
This is achieved by running the publisher and subscriber nodes as talker and listener which is declared in package.xml file. 
By running the below two commands in workspace which is sourced we get the terminal output.

Terminal 1: ros2 run py_pubsub talker
Terminal 2: ros2 run py_pubsub talker

<img width="789" height="370" alt="image" src="https://github.com/user-attachments/assets/893df5f3-3209-4769-8c4b-1b32e6acc572" />
