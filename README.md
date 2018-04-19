# aeroros

Build ROS packages:

cd ~/catkin_ws
catkin_make -j1

Enable systemd service roscore (if not enabled):
sudo systemctl enable /home/brian/workspace/src/aeroros/deploy/roscore.service
sudo systemctl start roscore


Enable systemd service aeroros:

sudo systemctl enable /home/brian/workspace/src/aeroros/deploy/aeroros.service
sudo systemctl start aeroros