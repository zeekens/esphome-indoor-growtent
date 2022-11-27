# esphome-indoor-growtent

This project aims to solve the problem that some bonsai trees needs lower temperatures but still lots of light during the winter months.

![Citrus-tree](https://user-images.githubusercontent.com/91693276/204163831-a3fb1ad1-b60b-4d5a-a33b-9b23e95b8c53.jpeg)
![growtent-crop](https://user-images.githubusercontent.com/91693276/204163854-8ee72050-2ad7-4676-8234-5870b4a9c894.jpg)


An ESP32 is used to control a COB LED strip so Home Assistant can run the automations. Included is also a Dallas temperature sensor to keep track of the soil temp and a  DHT11 for ambient temp and humidit. 

It is powered by a 24V DC plug and a buck converter to go down to 5V for the ESP board. Both temp sensors ru of off the 3.3V rail from the EPS32.

Parts List:

1: [IKEA Hyllis with cover](https://www.ikea.com/se/sv/p/hyllis-hylla-med-oeverdrag-transparent-s99291745/)

2: [DHT11 Sensors](https://www.amazon.se/AZDelivery-temperatursensor-fuktighetssensor-kompatibel-Raspberry/dp/B078S7FCZ9/ref=asc_df_B078S7FCZ9/?tag=shpngadsglede-21&linkCode=df0&hvadid=476458787949&hvpos=&hvnetw=g&hvrand=11650567471273787067&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1012697&hvtargid=pla-830325338865&psc=1)

3: [Dallas temp sensors](https://www.amazon.se/gp/product/B07CZ1G29V/ref=ppx_yo_dt_b_asin_title_o00_s02?ie=UTF8&psc=1)

4: [DC-DC Buck converters](https://www.amazon.se/Yizhet-omvandlare-str%C3%B6mf%C3%B6rs%C3%B6rjning-ned%C3%A5tomvandlare-ned%C3%A5tmodul/dp/B0823P6PW6/ref=sr_1_5?crid=2BTDN1V2QMQIN&keywords=buck+converter&qid=1669588828&qu=eyJxc2MiOiI1LjI3IiwicXNhIjoiNC40MCIsInFzcCI6IjQuMDIifQ%3D%3D&sprefix=buck+%2Caps%2C83&sr=8-5)

5: [Power Jacks](https://www.amazon.se/gp/product/B0975TSZRV/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)

6: [24V Power Adapter](https://www.amazon.se/gp/product/B07TLY8CJT/ref=ppx_yo_dt_b_asin_title_o02_s01?ie=UTF8&psc=1)

7: [Mosfet Boards](https://www.amazon.se/gp/product/B07VRCXGFY/ref=ppx_yo_dt_b_asin_title_o02_s02?ie=UTF8&psc=1)

8: [T-splitters](https://www.amazon.se/gp/product/B07WHC73R6/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1)

9: [ESP32](https://www.amazon.se/gp/product/B07VJ34N2Q/ref=ppx_yo_dt_b_asin_title_o07_s01?ie=UTF8&psc=1)


Fusion 360 models and stl files for the Enclosure is included. 

![ESP32-enclosure](https://user-images.githubusercontent.com/91693276/202304060-b2eb8c19-9488-461b-a21b-8b9d011347d1.jpg)

