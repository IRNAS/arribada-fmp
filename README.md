# Arribada Fish Monitoring Platform
Arribada Fish Monitoring Platform is a standalone off-grid device featuring a Raspberry Pi and a range of sensors and cameras. In this particular implementation it is designed for measuring the ater level by being suspended above a river and reporting values via satellite and lora networks as well as taking some webcam images.

Arribada Fish Monitoring Platform operation:
1) wake up in predefined intervals ~2h
2) measure water level with ultrasonic sensor MaxBotix Maxbotix Weather-Resistant Ultrasonic Rangefinder (MB7092XL-MaxSonar-WRMA1
3) capture an imate with raspberry pi camera
4) measure system parameters (battery voltage, charging status), show on LCD display
5) send message via Lora network using RMF95
6) send message via RockBlock Iridium modem
7) go to sleep

<img src="/pics/IMG_20170929_141407.jpg"  width="500px" height="375px">

<span><img
src="/pics/IMG_20170929_141339.jpg"  width="400px" height="300px">
<img
src="/pics/IMG_20170929_140921.jpg"  width="400px" height="300px"></span>


## <a href="https://github.com/IRNAS/arribada-fmp/tree/master/IoT%20battery%20pack%20v1.2%20pinout">With IoT battery pack v1.2</a>

<img src="/IoT%20battery%20pack%20v1.2%20pinout/pics/IMG_20171025_102726.jpg"  width="500px" height="375px">

## <a href="https://github.com/IRNAS/arribada-fmp/tree/master/PiRA%20Zero%20pinout">With PiRA Zero</a>

<img src="/PiRA%20Zero%20pinout/pics/IMG_20171025_102748.jpg"  width="500px" height="375px">
