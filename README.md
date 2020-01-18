# PI_WEBIO_680
This project allows users to control LED lighs with internet connection.
Team Members: Jacob, Patrick, 
#oct,24 charlie add comments here
#add through website

Flow :
Step 1: setup Raspberry pi, check git is ready and installed. if not
host> sudo apt install git
Step 2: make a new directory name git_work
host> mkdir git_work; cd git_work
Step 3: Git clone project in local PC
git clone https://github.com/zhouhaohua/PI_WEBIO_680.git
Step 4: start the flask sever
python3 gpio_app.py
step 5: connect LED series with 100ohm with Rasperry pin GPIO 13/19/26/ground
step 6: check 127.0.0.1:5000 , it should show the webio webpage
toggle ledRed on/ off show see toggle
step 7: check IP address by ifconfig
step 8: login in router by admin change the virtual server, add 5000 port as http port
and related IP addrress for step 7
step 9: register DDNS web by no ip, choose like (blanket).sytes.net as domain name
step 10: access (blanket).sytes.net:5000 to control the LED through any browser

[refer to]
https://hackaday.io/project/156072-raspberry-pi-3-as-a-web-server-using-python-iot

