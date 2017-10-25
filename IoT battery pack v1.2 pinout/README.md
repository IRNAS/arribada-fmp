# IoT battery pack v1.2 pinout

## Raspberry Pi Zero W pinout

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/Raspberry%20Pi%20Zero%20W%20pinout%202x10.png"  height="100px">

Connection to LCD Display:
 * 1 - 3V3 to LCD Display VCC (red)

Connection to RTC Module:
 * 3 - SDA to RTC Module SDA (orange)
 * 5 - SCL to RTC Module SCL (yellow)
 * 9 - GND to RTC Module GND (brown)

Connection to Battery Pack:
 * 4 - 5V to Battery Pack 5Vout (red)
 * 6 - GND to Battery Pack GND (black)

Connection to Satcomm Module RockBLOCK Mk2:
 * 2 - 5V to Satcomm Module RockBLOCK Mk2 5Vin (purple)
 * 8 - UART TXD to Satcomm Module RockBLOCK Mk2 TXD (green)
 * 10 - UART RXD to Satcomm Module RockBLOCK Mk2 RXD (blue)
 * 12 - GPIO18 to Satcomm Module RockBLOCK Mk2 Ring Indicator (white)
 * 14 - GND to Satcomm Module RockBLOCK Mk2 GND (grey)

Connection to Ultrasonic Sensor MaxBotix:
 * 15 - GPIO22 to Ultrasonic Sensor MaxBotix TX (blue)
 * 17 - 3V3 to Ultrasonic Sensor MaxBotix VCC (purple)
 * 20 - GND to Ultrasonic Sensor MaxBotix GND (grey)

Not connected:
 * 7 - GPIO4 (NC)
 * 11 - GPIO17 (NC)
 * 13 - GPIO27 (NC)
 * 16 - GPIO23 (NC)
 * 18 - GPIO24 (NC)
 * 19 - GPIO10 (NC)
 * 21-40 (NC)

## Satcomm Module RockBLOCK Mk2 pinout

<img src="/pics/Satcomm%20Module%20RockBLOCK%20Mk2%20pinout%201x6%20%2B%201x8.png"  height="60px">

Connection to Raspberry Pi Zero W:
 * 1 - RTS (NC)
 * 2 - RXD to Raspberry Pi Zero W UART RXD (blue)
 * 3 - TXD to Raspberry Pi Zero W UART TXD (green)
 * 4 - VCC (NC)
 * 5 - CTS (NC)
 * 6 - GND (NC)

Connection to Raspberry Pi Zero W:
 * 7 - GND to Raspberry Pi Zero W GND (grey)
 * 8 - 5Vin to Raspberry Pi Zero W 5V (purple)
 * 9 - 5Vout (NC)
 * 10 - Ring Indicator to Raspberry Pi Zero W GPIO18 (white)
 * 11 - NetAv (NC)
 * 12 - OnOff (NC)
 * 13 - LiIon (NC)
 * 14 - GND (NC)

## Ultrasonic Sensor MaxBotix pinout

<img src="/pics/Ultrasonic%20Sensor%20MaxBotix%20pinout%201x4.png"  height="60px">

Connection to Raspberry Pi Zero W:
 * 1 - GND to Raspberry Pi Zero W GND (grey)
 * 2 - VCC to Raspberry Pi Zero W 3V3 (purple)
 * 3 - RX (NC)
 * 4 - TX to Raspberry Pi Zero W GPIO22 (blue)

## Battery Pack pinout

<img src="/pics/Battery%20Pack%20pinout%202x5.png"  height="100px">

Connection to Raspberry Pi Zero W:
 * 1 - GND to Raspberry Pi Zero W GND (black)
 * 8 - 5Vout to Raspberry Pi Zero W 5V (red)

Connection to RTC Module:
 * 2 - GND to RTC Module GND (brown)
 * 6 - 3V3out to RTC Module VCC (red)
 * 7 - 5Ven to RTC Module SQW (purple)
 * 9 - SDA to RTC Module SDA (orange)
 * 10 - SCL to RTC Module SCL (yellow)

Not connected:
 * 3 - VBATen (NC)
 * 4 - VBAT (NC)
 * 5 - 3V3en (NC)

<img src="/pics/Battery%20Pack%20pinout%201x2.png"  height="60px">

Connection to power switch:
 * 1 - to power switch (red)
 * 2 - to power switch (black)

## RTC Module pinout

<img src="/pics/RTC%20Module%20pinout%201x6.png"  height="60px">

Connection to Battery Pack:
 * 1 - 32K (NC)
 * 2 - SQW to Battery Pack 5Ven (purple)
 * 3 - SCL to Battery Pack SCL (yellow)
 * 4 - SDA to Battery Pack SDA (orange)
 * 5 - VCC to Battery Pack 3V3out (red)
 * 6 - GND to Battery Pack GND (brown)

<img src="/pics/RTC%20Module%20pinout%201x4.png"  height="60px">

Connection to Raspberry Pi Zero W:
 * 1 - SCL to Raspberry Pi Zero W SCL (yellow)
 * 2 - SDA to Raspberry Pi Zero W SDA (orange)
 * 3 - VCC (NC)
 * 4 - GND to Raspberry Pi Zero W GND (brown)

<img src="/pics/RTC%20Module%20pinout%201x4.png"  height="60px">

Connection to LCD Display:
 * 1 - SCL to LCD Display SCL (yellow)
 * 2 - SDA to LCD Display SDA (orange)
 * 3 - VCC (NC)
 * 4 - GND to LCD Display GND (brown)

## LCD Display pinout

<img src="/pics/LCD%20Display%20pinout%201x4.png"  height="60px">

Connection to Raspberry Pi Zero W:
 * 1 - VCC to Raspberry Pi Zero W 3V3 (red)

Connection to RTC Module:
 * 2 - GND to RTC Module GND (brown)
 * 3 - SCL to RTC Module SCL (yellow)
 * 4 - SDA to RTC Module SDA (orange)
