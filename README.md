# esphome-indoor-growtent

This project aims to solve the problem that some bonsai trees needs lower temperatures but still lots of light during the winter months.

An ESP32 is used to control a COB LED strip so Home Assistant can run the automations. Included is also a Dallas temperature sensor to keep track of the soil temp and a  DHT11 for ambient temp and humidit. 

It is powered by a 24V DC plug and a buck converter to go down to 5V for the ESP board. Both temp sensors ru of off the 3.3V rail from the EPS32.

Fusion 360 models and stl files for the Enclosure is included. 

![ESP32-enclosure](https://user-images.githubusercontent.com/91693276/202304060-b2eb8c19-9488-461b-a21b-8b9d011347d1.jpg)

