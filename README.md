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

<img src="/pics/afmp-with-solar-module.png"  width="850px">

<img src="/pics/arribada-fmp-1.jpg"  width="425"> <img src="/pics/arribada-fmp-2.jpg"  width="425">  

<img src="/pics/arribada-fmp-3.jpg"  width="425"> <img src="/pics/arribada-fmp-4.jpg"  width="425">  

## <a href="https://github.com/IRNAS/arribada-fmp/tree/master/PiRA%20Zero%20pinout">With PiRA Zero</a>

<img src="/PiRA%20Zero%20pinout/pics/IMG_20171025_102748.jpg"  width="425">
