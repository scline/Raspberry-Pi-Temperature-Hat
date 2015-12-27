# Raspberry-Pi Temperature Sensor Hat
This repo is to track and update the progress of a custom PCB application to use with the Raspberry Pi system. The purpose is to attach multiple temperature sensors to create a wi-fi based monitor.

## Change Log
v1.0 - Initial board release for Raspberry Pi 2 / A+ models

## Software Used
To create the board I used the free version of [Eagle](http://www.cadsoftusa.com/eagle-pcb-design-software/about-eagle/). All you need to do is import the folder to load and start editing.

## Ordering PCB
There are many services that can create and print this board for you, I used [oshpark](https://oshpark.com/) due to ease of use and cheap processing. It was ~$30 to print this board (you get 3 of them whith your order) so it came out to about $10 each. You can get a 3D version of this board by using [EagleUP](https://eagleup.wordpress.com/installation-and-setup/)

## Parts 
The following parts are requred to complete this board. Links are just used as examples - ebay and other sites likely have these parts cheaper if you can wait for shipping.
* 1x [GPIO Header for Raspberry Pi A+/B+/Pi 2 - 2x20 Female Header](https://www.adafruit.com/products/2222)
* 3x [USB-A Jack*](https://www.adafruit.com/products/2225) 
* 3x [USB-A Connector*](https://www.adafruit.com/products/1387) 
* 3x [Dallas DS18B20 Sensors*](http://www.amazon.com/gp/product/B00CHEZ250?keywords=DS18B20&qid=1451202686&ref_=sr_1_1&sr=8-1)
* 1x [4.7k Resisitor*](https://www.adafruit.com/products/2783)
* 1x [DHT22 Sensor](http://www.amazon.com/SMAKN%C2%AE-Digital-Temperature-Humidity-Measurement/dp/B00MIBRFTI/ref=sr_1_1?ie=UTF8&qid=1451202874&sr=8-1&keywords=DHT22)
* 1x [10k Resistor](https://www.adafruit.com/products/2784) 

*You may need less depending on how manny sensor cords you want, if you only need 1 sensor then you can get away with just the 10k resistor + DHT22 sensor5


## Printed Circuit Board v1.0
Below is the 2D versions of this board rendered by Eagle software.

<img src="https://github.com/scline/Raspberry-Pi-Temperature-Hat/blob/master/Pi_Temp_v1.0/eagleUp/eagleUp_RasPi-BplusHAT_board_top.png?raw=true" width="450">
<img src="https://github.com/scline/Raspberry-Pi-Temperature-Hat/blob/master/Pi_Temp_v1.0/eagleUp/eagleUp_RasPi-BplusHAT_board_bottom.png?raw=true" width="450">

Here is the board when all the devices are soldered on:

<img src="https://github.com/scline/Raspberry-Pi-Temperature-Hat/blob/master/Pi_Temp_v1.0/pictures/complete.PNG?raw=true" width="600">