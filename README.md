# EMBEDDED SYSTEM
## IOT BASED TEMPERATURE AND HUMIDITY MEASUREMENT SYSTEM
### INTRODUCTION
The temperature and humidity of an environment is of uttermost importance to humans, getting to know the current temperature and humidity of the air in the environment. We would be measuring the temperature and humidity by building a system using a list of components stated below.
#### STATEMENT OF PROBLEM
Humans are faced with the challenge of getting to know the temperature and humidity of the air in the environment, to enable them know when to turn on or turn off an air conditioner, generally to give them control over the temperature of their environment. Although some systems have been created to automatically tell the temperature of the environment, we are leveraging the DHT11 sensor and nodemcu to build a system to help solve the problem stated. In this project we would be using the nodemcu to create a communication between the hardware system developed and the google firebase (a database to hold data sent from the microcontroller), an MIT app would be created to fetch the current data from the microcontroller and display it to the user.
#### COMPONENTS TO USED
##### 1. ESP8266 nodemcu board:
![](https://components101.com/sites/default/files/components/ESP8266-NodeMCU.jpg)

The ESP8266 WiFi Module is a self contained SOC with integrated TCP/IP protocol stack that can give any microcontroller access to your WiFi network. It creates a communication between the hardware components and the database. It also houses the microcontroller that processes the software codes sent to the hardware components.

##### 2. DHT-11 Sensor:
![](https://cdn.filestackcontent.com/resize=width:430,height:430,fit:crop,align:center/ftcmpaLvTD29PrcDmhXT)

    DHT11 sensor measures and provides humidity and temperature values serially over a single wire. It can measure the relative humidity in percentage (20 to 90% RH) and temperature in degrees Celsius in the range of 0 to 50°C.
DHT11 is a 4-pin sensor, these pins are VCC, DATA, GND and one pin is not in use shown in fig above.

##### 3. BUZZER

![](https://www.pcboard.ca/image/cache/catalog/products/buzzers/piezo-buzzer/piezo-buzzer-01-551x551.jpg)

An arduino buzzer is also called a piezo buzzer. It is basically a tiny speaker that you can connect directly to an Arduino. You can make it sound a tone at a frequency you set. The buzzer produces sound based on the reverse of the piezoelectric effect.

##### 4. JUMPER WIRES AND A BREADBOARD:

![](http://hub360.com.ng/wp-content/uploads/2018/02/1-4-1.jpg)

Jumper wires are simply wires that have connector pins at each end, allowing them to be used to connect two points to each other without soldering. Jumper wires are typically used with breadboards and other prototyping tools in order to make it easy to change a circuit as needed.

![](https://cdn.sparkfun.com/r/600-600/assets/d/c/a/b/4/513a1dface395fa524000001.JPG)

A breadboard is used to build and test circuits quickly before finalizing any circuit design. The breadboard has many holes into which circuit components like ICs and resistors can be inserted.

#### SCHEMATIC VIEW OF THE CIRCUIT




