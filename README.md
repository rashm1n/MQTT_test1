# weather-master
Real Time weather monitoring using MQTT + Android

## Overview

Weather master is a real time weather monitoring app made using Android Studio. To provide the data for the application a Weather Monitoring device has been implemented using NodeMCU 1.0 + Temperature and Humidity Sensor. (Pictures of the device and screenshots are included at the bottom)

## Android Application

In this application eclipse's [Paho MQTT API](https://www.eclipse.org/paho/clients/python/docs/) is used create the MQTT client in Android Studio. It is a pretty straightforward process and a callback function is used to execute everytime the data is added to the MQTT broker.

## Graphing

For the graphing of data [MPAndroidChart Library](https://github.com/PhilJay/MPAndroidChart) is used cause it combines Android's Graph View with some excellent methods.  

## MQTT Broker
As the MQTT broker , I used [CloudMQTT](https://www.cloudmqtt.com/) cause it provides a free easy to use service with a simple interface. You can easily find how to implement [Paho MQTT](https://www.eclipse.org/paho/clients/python/docs/) with CloudMQTT.

## NodeMCU Device

[NodeMCU WiFi Module](https://www.ebay.com/itm/NodeMcu-Lua-WIFI-Internet-Things-development-board-based-ESP8266-CP2102-module/201542946669?epid=13003516518&hash=item2eece54f6d:g:EOIAAOSw4q9XT5mo)  and [DHT11 Temperature Sensor](https://www.ebay.com/itm/New-DHT11-Temperature-And-Relative-Humidity-Sensor-Module-For-Arduino/172129092132?epid=1051342374&hash=item2813b18224:g:hm0AAOSw401aDjdy) is used to demonstrate the basic functionality of this Application , many other weather sensors can also be added to increase the functionality. 

[PahoMQTT Client Library](https://pubsubclient.knolleary.net/api.html#publish1) has been used to set up the NodeMCU as a MQTT client.

## All are welcome to fork or do a pull-request ! :) 

# Images - Results

## Device
![pic1](https://raw.githubusercontent.com/ravindurashmin/weather-master/master/result_images/whole.jpg)
![pic2](https://raw.githubusercontent.com/ravindurashmin/weather-master/master/result_images/dht.jpg)
![pic3](https://raw.githubusercontent.com/ravindurashmin/weather-master/master/result_images/Node.jpg)

## Application
![pic4](https://raw.githubusercontent.com/ravindurashmin/weather-master/master/result_images/splash.png)
![pic5](https://raw.githubusercontent.com/ravindurashmin/weather-master/master/result_images/home.png)
![pic6](https://raw.githubusercontent.com/ravindurashmin/weather-master/master/result_images/graph.png)

