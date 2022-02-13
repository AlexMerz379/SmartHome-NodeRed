# SmartHome-NodeRed

![Weather](https://user-images.githubusercontent.com/71424781/153758811-51d94aa3-15f2-47fe-8f4f-fd06421da74a.JPG)
![Raspberry Pio data](https://user-images.githubusercontent.com/71424781/153758816-8dbc336c-b97f-4cac-8ace-aae0281e0d96.JPG)
![Environment](https://user-images.githubusercontent.com/71424781/153758819-6cac69bf-5b2c-4fe6-872d-94a73606abe4.JPG)


NodeRed Paletten:
-npm install node-red-contrib-telegrambot
-node-red-node-pi-neopixel
-node-red-contrib-rpi-shutdown
-node-red-contrib-cpu
-node-red-dashboard
-node-red-contrib-sun-position
-node-red-contrib-telegrambot
-node-red-node-ping
-node-red-contrib-alexa-home-skill
-node-red-contrib-pi-hole-remote

Node Neopixellibrary cmd (Install description):
sudo apt-get install scons
sudo apt-get install build-essential python-dev git scons swig
git clone https://github.com/jgarff/rpi_ws281x
cd rpi_ws281x/
sudo scons
cd python
sudo python setup.py build
sudo python setup.py install

Activate GPIO cmd:
sudo curl -sS get.pimoroni.com/unicornhat | bash

Alexa:
Dokumentation: https://alexa-node-red.bm.hardill.me.uk/docs

Matplot:
sudo apt-get install python3-pip python3-dev
sudo pip3 install matplotlib
sudo apt-get install python3-matplotlib
sudo pip3 uninstall matplotlib
sudo apt-get purge python3-matplotlib
