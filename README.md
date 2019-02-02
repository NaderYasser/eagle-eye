# eagle-eye

HOW TO INSTALL:
- Clone the repo
- Go to the project folder
- install python virtual environment with the following commend
sudo apt install virtualenv
- create your virtual environment
virtualenv -p python3 env
- activate your env 
source env/bin/activate
make sure that (env) shown before your username in the terminal
- install the dependancies 
pip3 install -r requirements.txt

HOW TO RUN:
python multi_object_tracking_slow.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt \--model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --video <video> --output <output video>
