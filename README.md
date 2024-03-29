# LED-Controller-BarrelJack
Controller for WS2812B LEDs specially made for monitor backlighting with [WLED](https://kno.wled.ge/) and [Lightpack](https://github.com/psieg/Lightpack).

[Video example @ YouTube](https://youtu.be/EE_DajBsjAQ)

Controller can be attached to VESA 75 / 100 monitor mount using the case included in this repo.

Firmware can be flashed without additional power supply connected to the barrel jack connector.

Controller uses two pin headers to control the power for the LEDs:
* Always on -> LEDs will always be powered by power supply
* USB Power present -> LEDs will be powered by power supply if 5V on USB connector is present
* Software Control -> LEDs can be switched on and off within WLED firmware (relay function on GPIO 15)

![Front](https://github.com/dtimber/LED-Controller-BarrelJack/blob/main/Pictures/Rendering.PNG)

Additional Parts required:
* 1x Power Supply with 5V (Current depends on LED stripe length) with 5.5 mm / 2.1 mm barrel jack connector for example: Mean Well GST60A05
* 1x USB Type A to C or Type C to C cable
* 3x M3 insert nuts (outer diameter: 4.6 mm / length: 6 mm) for the case
* 3x M3 screws (countersunk head e.g. ISO 10642 / length: 12 mm) for the case
* 1x connector 538-43645-0300 for the LED stripe cable
* 3x contacts 43030-0007 for the LED stripe cable
