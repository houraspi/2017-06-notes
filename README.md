## Some recent cool stuffs

* ["Resin" in Resin](https://resin.io/blog/resin-in-resin-how-to-make-a-literal-embedded-device/)
* [Raspberry Pi Looper-Synth-Drum…thing](https://www.raspberrypi.org/blog/raspberry-pi-looper/)
* [Latest MagPi](https://www.raspberrypi.org/magpi-issues/MagPi58.pdf)
* [Latest HelloWorld: The computing and digital making magazine for educators](http://s3-eu-west-1.amazonaws.com/rpi-magazines/issues/full_pdfs/000/000/003/original/HelloWorld02.pdf?1495793062)
* [Intro to Physical Computing class](https://txrxlabs.org/classes/253/raspberry-pi-101-intro-to-physical-computing/)


## Show and tell

* [Thermometer monitoring freezer](./thermometer-project-slides.pdf)
  * using the [DS18b20](https://www.amazon.com/Vktech-DS18b20-Waterproof-Temperature-Transmitter/dp/B00CHEZ250)
* Smart Garden, modular garden
  * TXRX classes for learning woodworking
  * Learned about gardening at [Finca Tres Robles](http://www.smallplaces.org/fincatresrobles/)
  * Weather station
    * [ESP8266](https://www.amazon.com/HiLetgo-Version-NodeMCU-Internet-Development/dp/B010O1G1ES)
    * [SparkFun Soil Moisture Sensor](https://www.sparkfun.com/products/13322)
* Touch interface for RFID control system
  * 7 inch capacitive touch screen from [AliExpress](https://www.aliexpress.com/), approximately $45
  * [Raspberry Pi Zero](https://www.raspberrypi.org/blog/raspberry-pi-zero/)
  * Runs
    * Raspbian Jessie Lite
    * Webpage loaded on the touch screen
    * Webserver with Node.js
      * Installation methods
        * https://blog.miniarray.com/installing-node-js-on-a-raspberry-pi-zero-21a1522db2bb
        * https://github.com/sdesalas/node-pi-zero
      * Controls the GPIO
    * xwindows
  * ARMv6 architecture makes it difficult to compile
    * [Electron](https://github.com/electron/electron) or
    * [node-webkit/NW.js](https://github.com/nwjs/nw.js/)
  * [i2c bus](https://www.i2c-bus.org/i2c-bus/)
    * used [i2c](https://www.npmjs.com/package/i2c)
