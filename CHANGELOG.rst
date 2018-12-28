^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pcl_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

ROS2 (2018-12-31)
------------------
* Changed package.xml and CMakeList.txt as per ROS->ROS2 migration guide 
* Changed msg files according to ROS2
* Replaced message_generation with rosidl_default_generators (rosidl_generate_interfaces)

0.2.0 (2014-04-09)
------------------
* clean up package.xml
* update maintainer info
* remove eigen dependency
* Merge pull request `#1 <https://github.com/ros-perception/pcl_msgs/issues/1>`_ from bulwahn/patch-1
* Contributors: Lukas Bulwahn, Paul Bovbel

0.1.0 (2013-07-09)
------------------
* Generate messages into the pcl_msgs namespace rather than the pcl namespace

0.0.3 (2012-12-15)
------------------
* fix deps for messages
* Updated for new <buildtool_depend>catkin<...> rule

0.0.2 (2012-11-26 18:50)
------------------------
* increasing version
* ros message generation prefix hack

0.0.1 (2012-11-26 17:48)
------------------------
* initial commit - pcl ROS messages
