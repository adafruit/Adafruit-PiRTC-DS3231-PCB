## Adafruit PiRTC Precise DS3231 Real Time Clock for Raspberry Pi PCB

<a href="http://www.adafruit.com/products/4282"><img src="assets/4282.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PiRTC Precise DS3231 Real Time Clock for Raspberry Pi. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4282

### Description

This is the best battery-backed real time clock (RTC) you can get that allows your Raspberry Pi project to keep track of time if the power is lost. Perfect for data-logging, clock-building, NTP servers, time-stamping, timers and alarms, etc. Equipped with a genuine DS3231 RTC, it works great with the Raspberry Pi and has native kernel support.

The datasheet for the DS3231 explains that this part is an "Extremely Accurate I²C-Integrated RTC/TCXO/Crystal". And, hey, it does exactly what it says on the tin! This Real Time Clock (RTC) is the most precise you can get in a small, low power package.

Most RTCs use an external 32kHz timing crystal that is used to keep time with low current draw. And that's all well and good, but those crystals have slight drift, particularly when the temperature changes (the temperature changes the oscillation frequency very very very slightly but it does add up!) This RTC is in a beefy package because the crystal is inside the chip! And right next to the integrated crystal is a temperature sensor. That sensor compensates for the frequency changes by adding or removing clock ticks so that the timekeeping stays on schedule.

Many "cheap" DS3231 RTC boards do not use genuine Maxim DS3231's - you'll get a non-calibrated RTC which does not maintain the timekeeping quality that is specified! We purchase these DS3231's from Maxim direct so we know they are 100% genuine.

Works perfectly with any Raspberry Pi (or similar single board linux computer) including the Pi 1, Pi 2, Pi 3, Pi 4, Pi Zero, A+, B+ etc.

* Fully assembled & tested PCB plugs directly into your Pi's GPIO pins - No soldering required!
* Will keep time for 5 years or more

Note: This product does not come with a CR1220 coin cell battery. We recommend you purchase a coin cell battery to use with this product.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
