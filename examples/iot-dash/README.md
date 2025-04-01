
# IoT Dashboard for Rainmeter
## Introduction

This Rainmeter Skin is based on the [illustro design](https://github.com/rainmeter/rainmeter/blob/master/Build/Skins/illustro/System/System.ini) by Poiru. It's based on the MqttClientPlugin. 

![](https://imgur.com/a/djY4kyV)

## Features
This skin displays the state of your IoT devices. The following states are included:

🟢  Online
🔴  Offline
🔵  Active
⚪  No connection

It's also possible to toggle the state of your devices (online <-> active) by clicking on them.

## Installation
1) Build the plugin or download it as a [binary](https://github.com/fvanroie/MqttClientPlugin/releases).
2) Install the plugin (copy to **%apdpdata%/Rainmeter/plugins**).
3) Copy the **iot-dash** folder into your **Skins** folder.
4) Edit **Connections.ini** to change your MQTT credentials and add your own devices  I wrote a [blogpost](https://joszuijderwijk.nl/iot-dash/) on how the code works.
5) Enjoy!
