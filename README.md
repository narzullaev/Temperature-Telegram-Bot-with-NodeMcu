# Turn On and Off the LED light using Google Assistant 

## Introduction 
In this tutotrial we will go through how to do one-way (Google Assistant to NodeMcu) communication with NodeMcu using Google Assistant. At the end of this tutorial you will be able to turn off and turn on the LED light using Google Assistant.  

## Prerequisites
In order to complete this tutorial, you will need to have NodeMcu ESP8266 Wi-Fi board, 1 LED light.

You will also need to perform the following tasks before you can start this guide:
- **Install [Google Assistant](https://itunes.apple.com/us/app/google-assistant/id1220976145?mt=8) if your are _iPhone_ user**
- **Install [Arduino IDE](https://www.arduino.cc/en/Main/Software) together with [NodeMcu](https://github.com/nodemcu/nodemcu-devkit/tree/master/Drivers) driver**: We will be using Arduino IDE to write and deploy our code to NodeMcu board and for this you should have Arduino IDE installed in your machine tgether with NodeMcu driver. 
- **Create an account at [IFTT](https://ifttt.com/)**: If This Then That, also known as IFTTT, is a free web-based service to create chains of simple conditional statements, called applets.
- **Create an account at [Adafruit](https://io.adafruit.com/)**: Adafruit will help us to recieve signals from IFTT to NodeMcu board. 

## Step One - Installing list of libraries to our Arduino IDE
There is a library manager in each Arduino IDE under **Sketch>Include Library>Manage Library** path. When you get there there wait a minute for Arduino to update the list of libraries. There is a search bar provided and you can search and instll the following libraries: 
- _ESP8266WiFi_
- _Adafruit_MQTT_

**Example**

![screenshot from 2018-09-10 17-13-39](https://user-images.githubusercontent.com/33327894/45288712-e9715d80-b51d-11e8-80a1-7a139485eedf.jpg)

## Step Two - Configuration of Adafruit and IFTT 
I assume you have already created accounts at Adafruit and IFTT. First we will start from Adafruit. 
For this go to **[Adafruit](https://io.adafruit.com) > Dashboard** Click **Actions** and **Create A New Dashboard** as shown below. You can give whatever name you want. In my case I named my dashboard as *Lights*

![screenshot from 2018-09-10 17-32-24](https://user-images.githubusercontent.com/33327894/45289499-e2e3e580-b51f-11e8-88b2-538c2835a237.jpg)

After you created a dashboard open that dashboard and you should be able to see a blank dashboard. There are a few button on the top right corner click **+** to add a newblock (*I already have them*). 

![screenshot from 2018-09-10 17-39-37](https://user-images.githubusercontent.com/33327894/45289790-a1a00580-b520-11e8-808b-e08815a2777c.jpg)





