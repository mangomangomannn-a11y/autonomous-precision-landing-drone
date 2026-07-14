# 7/11/26 - 7/13/26
## Days 1-3: Design, budget restriction influence, planning, researching, tad bit of CAD, 7/10/26 - 9 Hours
This is being written about 2 days late because I first had to learn the ropes of making my own github project and got more sidetracked on the drone itself rather than the neat setup of my github.
I've had the intent of building a drone with something special in its design for about 4 months but never got started due to school sidetracking me. However, once summer started, I couldn't decide what I wanted to build. I considered generative drone frame design, UAV based autonomous flight, however, I ultimately decided on a autonomous precision landing drone for two main reasons: For one, as an aspiring astronautical engineer, it is a similar "control" type of technology used in the Mars 2020 Perseverance Rover to autonomously identify landing targets, as well as in SpaceX's Falcon 9 landings. But an arguably more notable factor was budget. I needed a project that I could feel more comfortable affording, in which this precision landing drone felt more interesting than others, and is far more affordable than the alternatives.

## Design (So far):
<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/c760f96e-b4cb-4be7-a97d-9bd38fc56c7e" />
If you haven't already noticed, this is by no means a final design, before I add the other parts of the BOM to the CAD, I want to first finalize all the parts I plan on purchasing so ensure compatibility so I'm not wasting my time and money. I was able to find these open source designs for the 450 mm frame I plan on purchasing as well as the SpeedyBee, and now simply need to design a plate adapter for the SpeedyBee and later 3d print it when the all parts are finalized and ordered. However, once the parts are finalized I can truly begin on the full design process.

## Parts (As of 7/13/26):
| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| HAWK'S WORK F450 Drone Frame, 450mm Wheelbase Quadcopter Frame Kit with Landing Skid Gear (Pre-soldered) | 1 | $28.99 | [Link](https://www.amazon.com/dp/B09YQ4TM88) |
| SpeedyBee F405 V5 OX32 55A 30x30 Model Aircraft FC&ESC Stack | 1 | $93.99 | [Link](https://www.speedybee.com/speedybee-f405-v5-55a-stack/) |
| Deegoo-FPV GPS Compass Module+ NEO-M8N+ GPS BDS Module Precision APM Drone Control GPS Receiver FPV Flight Control Pixhawk Navigation Module for APM PIX PX4, Compatible with APM Port I2C MWC | 1 | $28.99 | [Link](https://www.amazon.com/dp/B08NY9JSZ3) |
| Readytosky 2212 920KV Brushless Motors CW CCW for F330 F450 F550 S500 S550 X525 DJI Phantom Quadcopter(4PCS) | 1 | $39.99 | [Link](https://www.amazon.com/dp/B075DD16LK) |
| SoloGood 1045 (10x4.5) Propellers. 16 Pieces(8CW, 8CCW) Red & Black 10 inch FPV Props for F450 F550 S550 S500 FPV Quadcopter Multirotor | 1 | $13.99 | [Link](https://www.amazon.com/dp/B091KGR9Z6) |
| OVONIC 3S LiPo Battery 3000mAh 11.1V 130C RC Battery with XT60 Connector | 1 | $36.99 | [Link](https://www.amazon.com/dp/B00DF2BL8H1) |
| B6AC Balance Battery Charger, B6 AC 80W Lipo Battery Balance Charger 6A Discharger, RC Car Battery Charger for NiMH/NiCD/LiPo/Li-ion LiFePO4 | 1 | $33.99 | [Link](https://www.amazon.com/dp/B0F3BSLY3K) |
| FLYSKY FS-i6X 10CH 2.4GHz RC Transmitter Controller with FS-iA6B Receiver Upgrade Cable for RC Boat Racing Drone (Mode_2) | 1 | $58.48 | [Link](https://www.amazon.com/dp/B07Z8VCB45) |
| Raspberry Pi 4 2GB Model B | 1 | $55.00 | [Link](https://www.canakit.com/raspberry-pi-4-2gb.html?cid=usd&src=raspberrypi) |
| Arducam for Raspberry Pi Camera Module 60fps Global Shutter 1.58MP IMX296 Camera with M12 Lens Equipped with 15-22pin FPC Flexible Cable for Raspberry Pi 5, 3, 4 A/B | 1 | $64.99 | [Link](https://www.amazon.com/dp/B0C3VGMTRH) |
| Fermerry 28 AWG Stranded Wire Spool 5ft Each 6 Colors Flexible 28 Gauge Silicone Hook up Wire Kit Electrical Tinned Copper Wire | 1 | $8.29 | [Link](https://www.amazon.com/dp/B089CR4SDM) |
| 18 Gauge Electrical Wire with Heat Shrink Tubing, 18 Awg Red and Black Tinned Copper Electric Stranded Wire 0.82mm² for Automotive House LED Lamp, Flexible PVC High Temp(10M/32.8FT) | 1 | $11.99 | [Link](https://www.amazon.com/dp/B0G4JWWVH7) |
| 3pcs 15 Pin 30cm 50cm 100cm FFC Ribbon Flexible Flat Cable for Camera Pi Camera Cable Long Extension Flexible Ribbon Cable | 1 | $8.16 | [Link](https://www.amazon.com/dp/B07DNYM8KC) |
| 3pcs 24V/12V to 5V DC-DC Step Down Module 5A USB Power Converter for Arduino Raspberry Pi... | 1 | $9.99 | [Link](https://www.amazon.com/dp/B0FXWLB3XX) |
| **Total Price (USD):** | | **$516.42** | |

I have decided on these parts for my BOM as of now, they are most likely subject to change as I am currently seeking feedback from other communities such as Reddit and HackClub as well as researching forums regarding each part. 

## 7/14/26
I have now received some suggestions on Reddit with multiple users suggesting I go to a 4s battery rather than a 3s especially for the load of what I'm carrying as well as the motors. This entails swapping out my current 1045 props to 8045 ones as well as spending an extra ~$35 in which I'm not particularly fond of spending unless mandatory; a 4s battery that is the same price as my current 3s battery has drops from a capacity of 3000mAh to 1550 mAh yielding roughly just over half the flight time than the 3s. I don't want to buy all the parts and see that the 3s isn't efficient as that is a far more expensive mistake where I would have a net loss of upwards of $100 if the 3s doesn't work. I'm not sure what to do in this situation and will ask more questions from other communities.
