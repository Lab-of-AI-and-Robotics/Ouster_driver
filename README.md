
# Ouster SDK
from [Original Repo](https://github.com/ouster-lidar/ouster_example.git), commit 02fe2a9

This driver is for ROS1 Kinetic/Melodic/Noetic.
[Up-to-date driver](https://github.com/ouster-lidar/ouster-ros) is available solely on ROS1 Noetic.

In this repository, the timestamp of the LiDAR topic is set to ROS time by default.

This repository contains Ouster SDK source code for connecting to and configuring ouster sensors,
reading and visualizing data, and interfacing with ROS.

* `ouster_client <ouster_client/>`_ contains an example C++ client for ouster sensors
* `ouster_pcap <ouster_pcap/>`_ contains C++ pcap functions for ouster sensors
* `ouster_viz <ouster_viz/>`_ contains a customizable point cloud visualizer
* `ouster_ros <ouster_ros/>`_ contains example ROS nodes for publishing point cloud messages
* `python <python/>`_ contains the code for the ouster sensor python SDK (``ouster-sdk`` Python package)


License
========

BSD 3-Clause License, `details <LICENSE>`_
