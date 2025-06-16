
Setup Oak-D Lite on Ubuntu

Reference Link : https://docs.luxonis.com/software/depthai/manual-install/#Manual%20DepthAI%20installation-Installing%20dependencies-Ubuntu%2FDebian

Step 1 : Install Dependencies for Ubuntu

sudo wget -qO- https://docs.luxonis.com/install_dependencies.sh | bash


Step 2 : Install DepthAI

python3 -m pip install depthai


git clone https://github.com/luxonis/depthai-python.git

cd depthai-python


cd examples

python3 install_requirements.py


Run example Code : 
python3 ColorCamera/rgb_preview.py


If this doesnt work, then try 

git checkout develop

cd examples

python3 install_requirements.py


Run example Code : 
python3 ColorCamera/rgb_preview.py




_____________ X ___________________



DepthAI ROS Setup 

Reference Link  : https://docs.luxonis.com/software/ros/depthai-ros/

Step 1 : 

sudo apt install ros-humble-depthai-ros

If not, install from source : https://docs.luxonis.com/software/ros/depthai-ros/build/


OR FOLLOW THIS REPO : https://github.com/westonrobot/depthai_ros
