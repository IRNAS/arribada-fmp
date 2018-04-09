# Arribada Freshwater Monitoring Platform
Arribada Freshwater Monitoring Platform (AFMP) is a standalone off-grid device featuring a Raspberry Pi and a range of sensors and cameras. In this particular implementation it is designed for measuring the ater level by being suspended above a river and reporting values via satellite and lora networks as well as taking some webcam images.

Arribada Freshwater Monitoring Platform operation:
1) wake up in predefined intervals ~2h
2) measure water level with ultrasonic sensor MaxBotix Maxbotix Weather-Resistant Ultrasonic Rangefinder (MB7092XL-MaxSonar-WRMA1
3) capture an imate with raspberry pi camera
4) measure system parameters (battery voltage, charging status), show on LCD display
5) send message via Lora network using RMF95
6) send message via RockBlock Iridium modem
7) go to sleep

<img src="/pics/afmp-with-solar-module.png"  width="800px">

![alt-text-1](/pics/arribada-fmp-1.jpg "title-1" width="200px") ![alt-text-2](/pics/arribada-fmp-2.jpg "title-2" width="200px")
<img
src="/pics/arribada-fmp-1.jpg"  width="400px" height="50%">

<img
src="/pics/arribada-fmp-2.jpg"  width="400px" height="50%">



## <a href="https://github.com/IRNAS/arribada-fmp/tree/master/PiRA%20Zero%20pinout">With PiRA Zero</a>

<img src="/PiRA%20Zero%20pinout/pics/IMG_20171025_102748.jpg"  width="425" height="375px">

<img src="/PiRA%20Zero%20pinout/pics/IMG_20171025_102748.jpg"  width="425">
