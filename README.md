# DHT11 Python Raspberry-pi
## Components
1. [Raspberry PI3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)
2. [DTH11 Sensor](https://www.adafruit.com/product/386), available amazon.in also
3. Bread Board
4. Jumper Wires

## Optional Components
1. HDMI Cable 1 meter
2. Keyboard and mouse
3. TV

## Prerequisites
See [Prerequisites](./PREREQ.md)

## Instructions

1. The aim of this project is to measure temperature and humidity using DHT11 sensor via Raspberry pi.
2. You will need a RasPi with the Rasbian OS, DHT11 Sensor, Jumper wires and a small bread board.
3. First take a bread board and insert the DHT11 sensor, Now connect the GPIO(General Purpose Input Output) pins as fallows.
  1. Take a jumper wire, connect the ground pin of the DHT11 to pin(6) of the Raspberry Pi.
  2. Take another jumper wire, connect the data pin of the DHT11 to pin(7) of the Raspberry Pi.
  3. And connect, the last pin of the DHT11 which is VCC(Voltage Common Collector) to pin(2) of the Raspberry Pi.
4. Now the circuit part is over Let's Jump to Programming part.

## First Look
![first-look](https://user-images.githubusercontent.com/46535652/53825943-7d882300-3f9d-11e9-9102-dfcbbf2af2c3.jpg)

Use virtual environment for this project, read more information virtual environment https://realpython.com/python-virtual-environments-a-primer/

## Examples
You can find the [EXAMPLE.py](./EXAMPLE.py)

## Execution
``` Bash
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python EXAMPLE.py
```
This project Licensed under MIT(./LICENSE.md)
