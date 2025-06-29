This is a camera sensor working well will gazebo.
As we know,gazebo's own camera does not have worked with zoom function.
Someone may have needs to simulation with zoom-camera.
Use these files to override your own gazebo sensor lib file(libgz-sensor9-xx)
Only gazebo ionic works (means sensor9) 
You need to advertise topic with "your_own_camera_topic/hfov"
