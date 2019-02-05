# Ball_Tracking
Using Raspberry Pi based robot and raspicam to find center of a ball and track it (robot rotates based on where it finds the ball to be in the frame of the camera input)

In this project, I created a ROS package containing two communicating nodes that enable a raspberry pi based robot
the robot to turn in place to follow a ball (i. e. turning around Z axis - Yaw). Also created a debugging node that allows my computer to display the processed image from the robot. Used image processing code from a previous repository - https://github.com/bimbraw/Ball-center-detection.git
