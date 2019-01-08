pcl_msgs
========
ROS package containing PCL-related messages 

  ROS2 Migration Chnages

    Following Chnages done with respect to ROS1 (Indigo Level) package.    

        1. Add changes in .msg files as per the ROS2 message format.
        2. Migrated CMakeList.txt and package.xml as per ROS2 migration guide
           Note: ROS2 is using rosidl_default_generators instead of old type message_generation (ROS1)

  Procedure to Build and Test

    1. Follow below steps to download and build the package 

        1.1 git clone -b ros2 https://github.com/sandiprakhasiya/pcl_msgs.git
        1.2 cd pcl_msgs
        1.3 source /opt/ros/crystal/setup.bash 
        1.4 colcon build

    2. Follow below steps to test the package 

        2.1 colcon test
        2.2 colcon test-result  # it shows result of all tests as (Summary: 503 tests, 0 errors, 0 failures, 0 skipped)
            Note : Check log/latest_test for more information        
