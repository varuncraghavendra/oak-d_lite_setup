Setup Oak-D Lite on Ubuntu

Step 1 : 

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


