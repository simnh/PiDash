# PiDash

## Installation

### Temperature Sensor DHT22

To read DHT22 data the new library adafruit-circuitpython-dht 3.7.0
did not work for me. However the old one Adafruit-DHT 1.4.0 did.

`sudo pip install Adafruit_DHT`

### For dash visualisation

You might need some other libraries:

`sudo apt install libatlas-base-dev`


Fix "Illegal instruction" error:

* numpy version 1.20.3
* pandas version 1.2

Worked for me. 

## For server setup

I followed this instruction to run the app on
a server:

https://www.techcoil.com/blog/how-to-deploy-python-3-flask-application-on-raspberry-pi-3-with-raspbian-stretch-lite-nginx-supervisor-virtualenv-and-gunicorn/
