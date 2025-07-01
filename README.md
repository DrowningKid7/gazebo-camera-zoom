This is a camera sensor working well with Gazebo.
As we know, Gazebo's own camera does not have worked with zoom function.
Someone may have needs to do simulation with a zoom-camera.
Use these files to override your own Gazebo sensor lib file (libgz-sensor9-xx)
Only Gazebo ionic works (means sensor9) 
You need to advertise topic with "your_own_camera_topic/hfov"

Camera in sensor8 is supported.
