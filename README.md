# rpi-lightbulp
A Raspberry Pi controlled light bulp

* Raspberry Pi Modell B
* [SainSmart 8 Channel DC 5V Relay](http://www.sainsmart.com/8-channel-dc-5v-relay-module-for-arduino-pic-arm-dsp-avr-msp430-ttl-logic.html)
* jumper wires (female to female)
* electrical cable
* terminal strips

Copy `lightbulp` to `/usr/local/sbin/lightbulp`.

```
raspberrypi ~ $ sudo lightbulp status
light bulb is off
raspberrypi ~ $ sudo lightbulp on
light bulb is on
raspberrypi ~ $ sudo lightbulp off
light bulb is off
```
