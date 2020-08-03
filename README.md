# Livestock Tracking system

The system is aimed to track the location of each livestock head. The main advantages of this system:

  - low power consumption
  - cell tower independence
  - high communication range
  - easy scalability
  - cheap equipment
  - made on open technologies
  - convenient control directly from the phone
  
  ![N|Solid](https://github.com/Ilya-Legchilin/Livestock-Tracking-System/blob/master/cattleV1.png)

The system is designed in such a way that terminal devices send location information on the air. If the signal reaches the so-called pillar, then the information is stored there until it is sent to the user. If the signal has not reached the “pillar”, then instead of the pillar, you need to consider another terminal device (in our case, a cow). This process can be repeated indefinitely. If user has a connection with any of pillars, his smartphone will download the infomation stored on the pillar. The end result is always the information transmitted to the user on the smartphone.
