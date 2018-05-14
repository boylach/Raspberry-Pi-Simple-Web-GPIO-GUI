# Raspberry-Pi-Simple-Web-GPIO-GUI
Simple Node.JS Webserver for controlling GPIOs of the Raspberry Pi

Tutorial (english): https://tutorials-raspberrypi.com/setup-raspberry-pi-node-js-webserver-control-gpios/

Tutorial (german): http://tutorials-raspberrypi.de/raspberry-pi-nodejs-webserver-installieren-gpios-steuern

![Raspberry Pi GPIO GUI](http://tutorials-raspberrypi.de/wp-content/uploads/Raspberry-Pi-Node.js-Webserver-GPIOS.png)

################

nodejs interface to control stepper motors from raspi
https://github.com/boylach/Raspberry-Pi-Simple-Web-GPIO-GUI.git

# base resource is this tutorial
https://github.com/tutRPi/Raspberry-Pi-Simple-Web-GPIO-GUI
https://tutorials-raspberrypi.com/setup-raspberry-pi-node-js-webserver-control-gpios/

Present motivation is to make a computer control interface for the scanner for now.
testing starting code works... 
	missing some js dependency; so doing apt-get update/upgrade... no effect
	doing npm install for express, serve-favicon, morgan, cookie-parser, body-parser... not fixed
	trying to update npm with: sudo npm update npm -g... 