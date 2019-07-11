# FeatherWing-pinouts
This repo contains a quickly put together list of pins used by Adafruit's FeatherWing boards.  It is probably incomplete and may contain errors.  Some boards have minimal detail because they're not really relevant to being run by a Pi, which is important because of.....reasons.

An "X" indicates that the pin is used, a "o" indicates that the pin is optional.  Optional pins may indicate that at least one pin must be used, but the precise pin which is used can vary.  All pin numbers are given relative to 328p Feather boards.

|Board|URL|BAT|EN|USB|4|3|2|10|9|6|5|SCL|SDA|RST|3V|Aref|GND|A0|A1|A2|A3|A4|A5|A6|A7|SCK|MOSI|MISO|RX|TX|7|Notes|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Adalogger RTC/SD|https://www.adafruit.com/product/2922|||||||X||||X|X||X||X|||||||||X|X|X|||||
|OLED 128x32|https://www.adafruit.com/product/2900||||||||X|X|X|X|X||X||X||||||||||||||||
|Neopixel 4x8|https://www.adafruit.com/product/2945|X||X| o| o| o| o| o|X| o| o| o||||X| o| o| o| o| o| o| o| o| o| o| o| o| o| o||
|Airlift|https://www.adafruit.com/product/4264| o|X|X|X|X|X| o|||||||X||X|||||||||X|X|X| o| o|||
|Ethernet|https://www.adafruit.com/product/3201|||||||X|||||||X||X|||||||||X|X|X|||||
|INA219|https://www.adafruit.com/product/3650|||||||||||X|X||X||X|||||||||||||||Pinout not explicitly stated|
|Music Maker|https://www.adafruit.com/product/3436|X||X||||X|X|X|X|||X|X||X|||||||||X|X|X||X|||
|Radio RFM|https://www.adafruit.com/product/3229|||| o| o|||||||||X||X| o| o| o| o| o| o| o||X|X|X||||Data pins are flexible depending on interrupts on the chip  3 required.  Power not explicitly noted  presumably 3v3 and GND?|
|Joy|https://www.adafruit.com/product/3632|||| o| o| o| o| o| o| o|X|X||X||X|||||||||||||||Interrupt pin optional  one needed|
|NeoPXL8|https://www.adafruit.com/product/3249|||||||||||||||||||||||||||||||Not relevant for the Pi?|
|Dotstar 6x12|https://www.adafruit.com/product/3449|X|X|X|X||X| o| o| o| o||||||X| o| o| o| o| o| o||| o| o||||||
|DC Motor + Stepper |https://www.adafruit.com/product/2927|||||||||||X|X||X||X||||||||||||||||
|Ultimate GPS|https://www.adafruit.com/product/3133|||||||||||||X|X||X||||||||||||X|X|||
|Prop Maker|https://www.adafruit.com/product/3988|X|X|X|X|X|X|X|X|X|X|X|X|X|X||X| o|||||||||||||||
|DS3231|https://www.adafruit.com/product/3028|||||||||||X|X|X|X||X||||||||||||||||
|Mini relay|https://www.adafruit.com/product/2923|||| o| o| o| o| o| o| o| o| o||X||X| o| o| o| o| o| o| o| o| o| o| o| o| o| o|Requires 1 (non latching) or 2 (latching) pins  all optional|
|ADXL343 + ADT7410 Sensor|https://www.adafruit.com/product/4147|||||||||||X|X||X||X|||||||||||||||Pinout not specified  guessed.|
|8-Channel PWM or Servo|https://www.adafruit.com/product/2928|||||||||||X|X||X||X||||||||||||||||
|AMG8833 IR Thermal Camera|https://www.adafruit.com/product/3622|||| o| o| o| o| o| o| o|X|X||X||X| o| o| o| o| o| o| o| o| o| o| o| o| o| o|Not explicit  but interrupt can go anywhere?|
|15x7 CharliePlex|https://www.adafruit.com/product/3138|||||||||||X|X||X||X||||||||||||||||
|Mini Color TFT with Joystick|https://www.adafruit.com/product/3321||||| o| o| o| o|X|X|||||||||||||||X|X|||||6 and 5 can optionally be reqired to optional pins|
|"0.54"" Quad Alphanumeric"|https://www.adafruit.com/product/3130|||||||||||X|X||X||X||||||||||||||||
|8x16 LED Matrix|https://www.adafruit.com/product/3149|||||||||||X|X||X||X||||||||||||||||
|"2.13"" Monochrome eInk / ePaper Display"|https://www.adafruit.com/product/4195|||||||X|X|X|X|||X|X||X|||||||||X|X|X||||Possibly not relevant to the Pi given the way it plugs in?|
|4-Digit 7-Segment |https://www.adafruit.com/product/3110|||||||||||X|X||X||X||||||||||||||||

