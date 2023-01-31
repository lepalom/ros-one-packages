This repository contains packages of ROS v1 for the $DEB_DISTRO distribution. Follow the instrucctions to add it in your system.

If you have gitpages activated
```bash
echo "deb [trusted=yes arch=amd64] https://lepalom.github.io/ros-one-packages bullseye  main | sudo tee /etc/apt/sources.list.d/lepalom_ros-one-packages.list
```
if not
```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/lepalom/ros-one-packages/bullseye-debian/ ./" | sudo tee /etc/apt/sources.list.d/lepalom_ros-one-packages.list
```
also, add the yaml contents
```bash
echo "yaml https://raw.githubusercontent.com/lepalom/ros-one-packages/bullseye-debian/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-lepalom_ros-one-packages.list
```

## Packages in the repository
[ros-ackermann-steering-controller]
 
[ros-actionlib-tutorials]
 
[ros-amcl]
 
[ros-apriltag-ros]
 
[ros-audio-capture]
 
[ros-audio-common]
 
[ros-audio-common-msgs]
 
[ros-audio-play]
 
[ros-backward-ros]
 
[ros-base-local-planner]
 
[ros-behaviortree-cpp]
 
[ros-boost-sml]
 
[ros-carrot-planner]
 
[ros-clear-costmap-recovery]
 
[ros-code-coverage]
 
[ros-combined-robot-hw]
 
[ros-combined-robot-hw-tests]
 
[ros-common-tutorials]
 
[ros-compressed-depth-image-transport]
 
[ros-compressed-image-transport]
 
[ros-controller-interface]
 
[ros-controller-manager]
 
[ros-controller-manager-msgs]
 
[ros-controller-manager-tests]
 
[ros-convex-decomposition]
 
[ros-costmap-2d]
 
[ros-diff-drive-controller]
 
[ros-driver-base]
 
[ros-driver-common]
 
[ros-dwa-local-planner]
 
[ros-eml]
 
[ros-ethercat-grant]
 
[ros-executive-smach]
 
[ros-executive-smach-visualization]
 
[ros-fake-joint]
 
[ros-fake-joint-driver]
 
[ros-fake-localization]
 
[ros-filters]
 
[ros-force-torque-sensor-controller]
 
[ros-forward-command-controller]
 
[ros-four-wheel-steering-msgs]
 
[ros-geometry-tutorials]
 
[ros-gl-dependency]
 
[ros-global-planner]
 
[ros-graph-msgs]
 
[ros-hardware-interface]
 
[ros-image-transport-plugins]
 
[ros-imu-sensor-controller]
 
[ros-interactive-marker-tutorials]
 
[ros-ivcon]
 
[ros-joint-limits-interface]
 
[ros-joint-state-controller]
 
[ros-joy]
 
[ros-joy-teleop]
 
[ros-joystick-drivers]
 
[ros-key-teleop]
 
[ros-laser-assembler]
 
[ros-laser-filters]
 
[ros-laser-pipeline]
 
[ros-librviz-tutorial]
 
[ros-map-server]
 
[ros-media-export]
 
[ros-mouse-teleop]
 
[ros-move-base]
 
[ros-move-slow-and-clear]
 
[ros-moveit]
 
[ros-moveit-commander]
 
[ros-moveit-msgs]
 
[ros-moveit-planners]
 
[ros-moveit-plugins]
 
[ros-moveit-resources]
 
[ros-moveit-resources-dual-panda-moveit-config]
 
[ros-moveit-resources-fanuc-description]
 
[ros-moveit-resources-fanuc-moveit-config]
 
[ros-moveit-resources-panda-moveit-config]
 
[ros-moveit-resources-pr2-description]
 
[ros-moveit-resources-prbt-moveit-config]
 
[ros-moveit-resources-prbt-pg70-support]
 
[ros-moveit-resources-prbt-support]
 
[ros-moveit-ros]
 
[ros-moveit-runtime]
 
[ros-nav-core]
 
[ros-navfn]
 
[ros-navigation]
 
[ros-nodelet-tutorial-math]
 
[ros-object-recognition-msgs]
 
[ros-octomap-msgs]
 
[ros-octomap-ros]
 
[ros-octomap-rviz-plugins]
 
[ros-openslam-gmapping]
 
[ros-plotjuggler]
 
[ros-plotjuggler-msgs]
 
[ros-plotjuggler-ros]
 
[ros-pluginlib-tutorials]
 
[ros-position-controllers]
 
[ros-qt-dotgraph]
 
[ros-qt-gui]
 
[ros-qt-gui-app]
 
[ros-qt-gui-core]
 
[ros-qt-gui-py-common]
 
[ros-qwt-dependency]
 
[ros-realtime-tools]
 
[ros-rgbd-launch]
 
[ros-ros-control]
 
[ros-ros-controllers]
 
[ros-ros-pytest]
 
[ros-ros-tutorials]
 
[ros-rosbag-migration-rule]
 
[ros-rosbag-snapshot]
 
[ros-rosbag-snapshot-msgs]
 
[ros-roscpp-tutorials]
 
[ros-rosdoc-lite]
 
[ros-roslint]
 
[ros-rosparam-shortcuts]
 
[ros-rospy-tutorials]
 
[ros-rotate-recovery]
 
[ros-rqt]
 
[ros-rqt-action]
 
[ros-rqt-bag]
 
[ros-rqt-bag-plugins]
 
[ros-rqt-common-plugins]
 
[ros-rqt-console]
 
[ros-rqt-controller-manager]
 
[ros-rqt-dep]
 
[ros-rqt-graph]
 
[ros-rqt-gui]
 
[ros-rqt-gui-py]
 
[ros-rqt-joint-trajectory-controller]
 
[ros-rqt-launch]
 
[ros-rqt-logger-level]
 
[ros-rqt-moveit]
 
[ros-rqt-msg]
 
[ros-rqt-nav-view]
 
[ros-rqt-plot]
 
[ros-rqt-pose-view]
 
[ros-rqt-publisher]
 
[ros-rqt-py-common]
 
[ros-rqt-py-console]
 
[ros-rqt-reconfigure]
 
[ros-rqt-robot-dashboard]
 
[ros-rqt-robot-monitor]
 
[ros-rqt-robot-steering]
 
[ros-rqt-runtime-monitor]
 
[ros-rqt-service-caller]
 
[ros-rqt-shell]
 
[ros-rqt-srv]
 
[ros-rqt-tf-tree]
 
[ros-rqt-top]
 
[ros-rqt-topic]
 
[ros-rqt-web]
 
[ros-ruckig]
 
[ros-rviz-plugin-tutorials]
 
[ros-rviz-python-tutorial]
 
[ros-rviz-visual-tools]
 
[ros-slam-gmapping]
 
[ros-smach]
 
[ros-smach-msgs]
 
[ros-smach-ros]
 
[ros-smach-viewer]
 
[ros-soem]
 
[ros-sound-play]
 
[ros-spacenav-node]
 
[ros-srdfdom]
 
[ros-teleop-tools]
 
[ros-teleop-tools-msgs]
 
[ros-theora-image-transport]
 
[ros-timestamp-tools]
 
[ros-transmission-interface]
 
[ros-turtle-actionlib]
 
[ros-turtlesim]
 
[ros-unique-id]
 
[ros-unique-identifier]
 
[ros-urdf-geometry-parser]
 
[ros-urdf-tutorial]
 
[ros-urdfdom-py]
 
[ros-uuid-msgs]
 
[ros-visualization-marker-tutorials]
 
[ros-visualization-tutorials]
 
[ros-voxel-grid]
 
[ros-warehouse-ros]
 
[ros-webkit-dependency]
 
