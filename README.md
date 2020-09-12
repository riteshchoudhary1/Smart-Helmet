# Smart-Helmet
> ## Received Honorary Mention Award in IEEE YESIST 12 Competition Held at Stanford University Thailand.
 
### SACHET is an IOT based cooling Helmet equipped with Safety and Protective features.

### `Objective :`
> #### To maintain the comfort of a rider in all weather conditions as well as adhere to the safety standards. Also To emphasize people to wear helmet even for small distances.

Features at a Glance:
- Cooling Mechanism using Peltier module
- Detachable Wiper
- Pre Alcohol Test
- Night assistant to avoid sleepiness
- SOS messaging feature (using GPS and GSM)
- Bluetooth Connectivity
- Defogging Mechanism

</br>

### Honorary Mention Award with cash prize of 100$ USD
---
![alt text](https://github.com/riteshchoudhary1/Smart-Helmet/blob/master/IEEE-YESIST-12/OnStage1.jpeg)

</br>

### `Team Trigger Mindscape`
---
![alt text](https://github.com/riteshchoudhary1/Smart-Helmet/blob/master/IEEE-YESIST-12/PresentationTable2.jpeg)
##### Mentor
- Dr. Y.P Patil
##### Members
   - Gaurav Sonavane
   - Shreyas Shah
   - Rishab Bhat
   - Ritesh Choudhary
   
### `Flow Diagram :`

![alt text](https://github.com/riteshchoudhary1/Smart-Helmet/blob/patch-1/Images/flowchart.png)

### `Design :`
![alt text](https://github.com/riteshchoudhary1/Smart-Helmet/blob/patch-1/Images/design.png)

| Components | Description|
| ----	| ----	|
| [Microcontroller ATmega328P](https://en.wikipedia.org/wiki/ATmega328) | **Heart of the system**<br> For a presentation version, we have used Arduino Uno which is a microcontroller board based on the ATmega328 and has huge support from the community, which make it easier to start working in embedded electronics.  |
| [Peltier Module](https://www.sunelectronics.co.in/Thermoelectric%20Peltier%20Refrigeration%20Cooling%20System%20DIY%20Kit)	| **For Controlling Warmness and Fogg**<br> Peltier module is used in order to increase comfortness with hot/cold air flowing through helmet. It operates on input voltage of 12V. |
| [Alcohol Sensor MQ135](http://juvtmall.com/wiki/mq135-gas-sensor-module_i0054.html)| **To avoid Drink and Drive Case**<br> Alcohol level gets automatically tested using alcohol sensor, if the level exceeds the given limit then the vehicle will not get started. |
| [Bluetooth Module HC-05](https://www.electronicwings.com/sensors-modules/bluetooth-module-hc-05-)  	| **Avoid use of phone**<br> An internal bluetooth is provided which display incoming calls on the display screen when connected. |
| [GSM/GPRS Module SIM900A](https://www.electronicwings.com/sensors-modules/sim900a-gsmgprs-module) | **SOS Help Feature**<br> In case of distress or fear, rider can send a message is send to emergency contact number with the GPS location, using this one click feature.   	|
| [Rain sensor and Wiper](https://www.electronicwings.com/sensors-modules/servo-motor)| **For Clear Vision During Rainy Season**<br> A Detachable wiper is mounted on Helmet, which starts automatically after sensing raindrops and keeps the glass clean.   	|
| [LCD Display Screen](https://www.electronicwings.com/sensors-modules/lcd-16x2-display-module)| **LCD 16x2 line Display Module**<br> It is one kind of electronic display module used in an extensive range of applications like various circuits and devices like calculators. |


### `Problems that we aim to resolve :`
- Decreased visibility of rider due to water droplets on shield.
- Suffocation due to heat. 
- Problem of fogg during winter.
- Dizziness while driving in night.
- Use of phone while driving.
- Issue of drunk and drive.

### `Constraints :`
The systems operates on 12V DC supply.<br>
Inorder to assemble it on bike it would require a power management system to ensure constant power supply.
