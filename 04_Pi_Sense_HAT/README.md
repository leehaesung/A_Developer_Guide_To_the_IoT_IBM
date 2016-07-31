# Raspberry Pi Sense HAT 

## DESCRIPTION
Control the same hardware as used in space...build your very own [Astro](https://astro-pi.org/) Pi with the new Raspberry Pi Sense HAT! The Raspberry Pi Sense HAT is attached on top of the Raspberry Pi via the 40 GPIO pins to create an ‘Astro Pi’. The Sense HAT has several integrated circuit based sensors can be used for many different types of experiments, applications, and even games. And it's being used in conjunction with the Raspberry Pi Foundation to perform science experiments aboard the International Space Station (ISS)!

### The sensors enable you to read:
* Gyroscope
* Accelerometer
* Magnetometer
* Barometric pressure
* Humidity
* Temperature

The Sense HAT supports a whole host of projects for the Raspberry Pi, it can measure how fast is the Pi itself travelling (i.e. measure your speed), how hot is it? how humid is it? (air humidity), which direction is the Raspberry Pi facing? And more.

The 8x8 LED Matrix enables you to display the data from the various sensors, it can show you which way is geomagnetic North by programming a compass using the magnetometer, or simply be used to play games like Tetris, Pong and Snake with the joystick. The joystick can also be used to enable a human user to interact with the programs running on the Raspberry Pi Sense HAT.

Writing programs for the Sense HAT is very simple with a Python library available to get started quickly and easily. For a truly out of world projects check out the [AstroPi website](https://astro-pi.org/), containing a host of ideas and instructions.

### To Install Python Library of Pi Sense HAT
* Install the Sense HAT software by opening a Terminal window and entering the following commands (while connected to the Internet):

``````````````````````````````
sudo apt-get update
sudo apt-get install sense-hat
sudo reboot
``````````````````````````````

* Hello world example:

``````````````````````````````
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Hello world!")
``````````````````````````````
See the [API reference](https://pythonhosted.org/sense-hat/api/) for full documentation of the library's functions. See [examples](https://github.com/RPi-Distro/python-sense-hat/blob/master/examples/README.md).



### To Install Bash:
* Connect your Sense HAT to the Raspberry Pi via the 40 GPIO Pins
* Open up a terminal and run the following command:

`wget -O - http://www.raspberrypi.org/files/astro-pi/astro-pi-install.sh --no-check-certificate | bash`
* (This will take approximately 5 minutes to run on the Raspberry Pi 2 Model B, and approximately 20 minutes on earlier models of the Raspberry Pi)
* When the install is finished you will need to reboot your Raspberry Pi

### Note:
The Raspberry Pi Sense HAT is compatible with the Raspberry Pi 3, [Raspberry Pi 2](https://www.adafruit.com/products/2358), [Model B+](https://www.adafruit.com/products/1914), and [Model A+](https://www.adafruit.com/products/2266), but NOT the earlier 26-pin models of Raspberry Pi 1 Model B & A's. Pi not included!


## TECHNICAL DETAILS
* Gyroscope
      * Angular rate sensor (dps): ~245/500/2000
* Accelerometer
      * Linear acceleration sensor (g): ~2/4/8/16
* Magnetometer
      * Magnetic sensor (gauss): ~4/8/12/16
* Barometer: 260 - 1260 hPa absolute range (accuracy depends on the temperature and pressure, ~0.1 hPa under normal conditions)
* Temperature sensor: Accurate to ~2°C in the 0-65°C range
* Relative humidity sensor: Accurate to ~4.5% in the 20-80%rH range, accurate to ~0.5°C in 15-40°C range
* 8x8 LED matrix display
* Small 5 button joystick

### For product support, replacement parts and warranty for [Raspberry Pi products visit the Raspberry Pi Help Page](https://www.raspberrypi.org/products/sense-hat/) or contact the [Pi Foundation directly on their forums](https://www.raspberrypi.org/forums/).
* Product Dimensions: 65.1mm x 56.6mm x 13.9mm / 2.6" x 2.2" x 0.5"
* Product Weight: 20.4g / 0.7oz
* Visit the [Python Library.](http://pythonhosted.org/sense-hat/)
* [Official GitHub](https://github.com/leehaesung/python-sense-hat)


< END >
