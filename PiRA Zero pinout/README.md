# PiRA Zero pinout

<img src="/PiRA%20Zero%20pinout/pics/IMG_20171025_102748.jpg"  width="500px" height="375px">

## Raspberry Pi Zero W pinout

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/Raspberry%20Pi%20Zero%20W%20pinout%202x10.png"  height="100px">

Connection to Ultrasonic Sensor MaxBotix:
 * 15 - GPIO22 to Ultrasonic Sensor MaxBotix TX (blue)
 * 17 - 3V3 to Ultrasonic Sensor MaxBotix VCC (purple)
 * 20 - GND to Ultrasonic Sensor MaxBotix GND (grey)

Not connected:
 * 1-14, 16, 18, 19, 21-40 (NC)

## PiRA Zero pinout

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/Battery%20Pack%20pinout%202x5.png"  height="100px">

Connection to Satcomm Module RockBLOCK Mk2:
 * 2 - UART RXD to Satcomm Module RockBLOCK Mk2 RXD (blue)
 * 3 - UART TXD to Satcomm Module RockBLOCK Mk2 TXD (green)

Connection to Satcomm Module RockBLOCK Mk2:
 * 1 - OUT- to Satcomm Module RockBLOCK Mk2 GND (grey)
 * 2 - OUT+ to Satcomm Module RockBLOCK Mk2 5Vin (purple)

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/LCD%20Display%20pinout%201x4.png"  height="60px">

Connection to LCD Display:
 * 1 - GND to LCD Display GND (brown)
 * 2 - SCL to LCD Display SCL (yellow)
 * 3 - SDA to LCD Display SDA (orange)
 * 4 - 3V3 to LCD Display VCC (red)

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/Battery%20Pack%20pinout%201x2.png"  height="60px">

Connection to power switch:
 * 1 - to power switch (red)
 * 2 - to power switch (black)

## Ultrasonic Sensor MaxBotix pinout

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/Ultrasonic%20Sensor%20MaxBotix%20pinout%201x4.png"  height="60px">

Connection to Raspberry Pi Zero W:
 * 1 - GND to Raspberry Pi Zero W GND (grey)
 * 2 - VCC to Raspberry Pi Zero W 3V3 (purple)
 * 3 - RX (NC)
 * 4 - TX to Raspberry Pi Zero W GPIO22 (blue)
 
 ## Satcomm Module RockBLOCK Mk2 pinout

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/Satcomm%20Module%20RockBLOCK%20Mk2%20pinout%201x6%20%2B%201x8.png"  height="60px">

Connection to PiRA Zero:
 * 1 - RTS (NC)
 * 2 - RXD to PiRA Zero UART RXD (blue)
 * 3 - TXD to PiRA Zero UART TXD (green)
 * 4 - VCC (NC)
 * 5 - CTS (NC)
 * 6 - GND (NC)

Connection to PiRA Zero:
 * 7 - GND to PiRA Zero OUT- (grey)
 * 8 - 5Vin to PiRA Zero OUT+ (purple)
 * 9 - 5Vout (NC)
 * 10 - Ring Indicator (NC)
 * 11 - NetAv (NC)
 * 12 - OnOff (NC)
 * 13 - LiIon (NC)
 * 14 - GND (NC)

 ## LCD Display pinout

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/LCD%20Display%20pinout%201x4.png"  height="60px">

Connection to PiRA Zero:
 * 1 - VCC to PiRA Zero 3V3 (red)
 * 2 - GND to PiRA Zero GND (brown)
 * 3 - SCL to PiRA Zero SCL (yellow)
 * 4 - SDA to PiRA Zero SDA (orange)
