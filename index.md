**Make Electronics Class - August 8, 2026**

Class Slides [PDF](https://makesantafe.github.io/classnotes/2026_08_08inputsoutputsmotors.pdf)
Make Electronics [Wiki](https://wiki.makesantafe.org/en/resources/electronics) (has the same information that is found below)

# Electronics Classes Links and Resources
## Class Links
- MicroBlocks [website](https://microblocks.fun)
- Micro:bit [bare board](https://www.amazon.com/BBC-Micro-Programming-Include-Battery/dp/B0BSF5KTLT)
- Micro:bit [motor driver board](https://www.amazon.com/KEYESTUDIO-Motor-Drive-Breakout-Board/dp/B07BQPC9ZV)
- Cutebot Pro [Robot Car](https://www.amazon.com/Elecfreaks-Microbit-Smart-Cutebot-Micro/dp/B081ZSCZTV)
- An inexpensive [adjustable power supply](https://www.amazon.com/dp/B08N46GMM8)
- A medium expensive [adjustable power supply](https://www.amazon.com/NICE-POWER-Adjustable-Switching-Regulated-Adjustments/dp/B0CDW12H3X)
- ESP32 [temperature sensor](https://www.amazon.com/dp/B01DKC2GQ0) / sensor [kit](https://www.amazon.com/SunFounder-Compatiple-Beginners-Engineers-ESP32-WROOM-32E/dp/B0CLDJ2DL7) / another sensor [kit](https://www.amazon.com/LAFVIN-Starter-Development-Tutorial-Compatible/dp/B0BVZBTP8V)
- A USB-C [soldering iron](https://www.amazon.com/PINECIL-Smart-Mini-Portable-Soldering/dp/B096X6SG13) / less expensive plug-in [soldering kit](https://www.amazon.com/Soldering-Interchangeable-Adjustable-Temperature-Enthusiast/dp/B087767KNW )
- An inexpensive [multimeter](https://www.amazon.com/dp/B0BYD32JZV)
- A solid state [relay](https://www.amazon.com/10pcs-Solid-State-Relay-Input/dp/B0DK36RT9K) to control larger electrical devices from an ESP32
- LED "Neopixel" (WS2812) [rings](https://www.amazon.com/DIYmall-Integrated-Individually-Addressable-Raspberry/dp/B0B2D6JDVJ) / or longer [strips](https://www.amazon.com/WS2812B-addressable-Neopixe-Non-Waterproof-144led/dp/B09MKSVV5H)
- A 5 volt, 2 amp [power supply](https://www.amazon.com/Supply-Adapter-100-240V-Electronic-Devices/dp/B0FMFXHYJ3) for longer LED strips up to around 30 LEDs
- An [audio board](https://www.adafruit.com/product/2133) that plays back audio files when triggered
- If you would like to make something with the ESP32 that's a little more permanent, this ["ElectroCookie" board](https://www.amazon.com/dp/B07ZYNWJ1S) is halfway between a breadboard and making your own circuit board
- To create a socket on this board for an ESP32 (or any circuit board), a [kit like this](https://www.amazon.com/dp/B0B96WXT46) might be the least expensive way
- To control the speed of AC motors you need a ["variac"](https://www.amazon.com/VEVOR-Variable-Transformer-Regulator-Industrial/dp/B0CZ3NTMJQ)
- A [semiconductor based variac](https://www.amazon.com/Controller-Variable-Electronic-Regulator-Protection/dp/B0CKFK68X9)that can work for many types of AC motors

**ESP32 Resources**

[Getting Started on Random Nerds Website](https://randomnerdtutorials.com/getting-started-with-esp32/)
[Pinout Guide on Random Nerds Website](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)

**ESP32 Tips and Tricks for MicroBlocks**

*(Re-)Programming an ESP32 to Work with MicroBlocks*
- In MicroBlocks go under the "gear" menu, select "advanced mode," then go under the "gear" menu again and select "erase flash and update firmware on ESP32." 
- Hold down the tiny "BOOT" button on the ESP32 while selecting the port and clicking "Connect."
- Wait for the reprogramming to finish before doing anything else (don't switch tabs in Chrome or run another program).
- Unplug the ESP32 and plug it in again before reconnecting to MicroBlocks. 
- If this doesn't work, try doing the "factory reset" procedure below first and then repeat the procedure above. 
- Use the ["factory reset" tool from Adafruit](https://learn.adafruit.com/adafruit-esp32-s2-feather/factory-reset#step-3-alternative-a-the-adafruit-webserial-esptool-method-3107291). It requires using the Google Chrome browser and holding down the "Boot" button on the ESP32 until the tool connects. Then clicking the "Erase" button completely resets the ESP32. 

*More Tips*
- Choose pins that are typically safe to use by referencing [this tutorial](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)
- Input/output pins: 4, 5, 13, 14, 18, 19, 21, 22, 23, 25, 26, 27, 32, 33
- Digital to analog pins: 25 and 26
- Input only pins: 34-39 (DHT11 issue)
- I2C SDA/SCL: Pin 21 and 22
- If using WiFi, don't use 12-15, 25-27

*Buying the "Right" ESP32*
- MicroBlocks only works with the ESP32, ESP32-S3, and ESP32-C3 (there are many more [versions](https://www.xda-developers.com/more-than-one-esp32-differences-between-all) that don't work with MicroBlocks)
- It's best to stick to the [original/38 pin/25mm](https://www.amazon.com/ESP-WROOM-32-Development-Dual-Mode-Microcontroller-Integrated/dp/B0718T232Z) ESP32 model (the wider/30 pin/28mm ESP32 doesn't fit on a breadboard)
- When using an ESP32 with a breadboard, print this [pinout chart](https://makesantafe.github.io/classnotes/ESP32pinout.jpg) (3" high) and use it as a template because the narrow version doesn't have pin numbers on top**

If you're not using MicroBlocks, there are [more ESP32's](https://www.xda-developers.com/more-than-one-esp32-differences-between-all/) and a whole [YouTube video](https://www.youtube.com/watch?v=u5unB24lhC4) on the various types!
