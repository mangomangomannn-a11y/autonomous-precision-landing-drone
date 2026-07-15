# 7/11/26 - 7/13/26
## Days 1-3: Design, budget restriction influence, planning, researching, tad bit of CAD, 7/10/26 - 9 Hours
This is being written about 2 days late because I first had to learn the ropes of making my own github project and got more sidetracked on the drone itself rather than the neat setup of my github.
I've had the intent of building a drone with something special in its design for about 4 months but never got started due to school sidetracking me. 

However, once summer started, I couldn't decide what I wanted to build. I considered generative drone frame design, UAV based autonomous flight, however, I ultimately decided on a autonomous precision landing drone for two main reasons: For one, as an aspiring astronautical engineer, it is a similar "control" type of technology used in the Mars 2020 Perseverance Rover to autonomously identify landing targets, as well as in SpaceX's Falcon 9 landings. But an arguably more notable factor was budget. I needed a project that I could feel more comfortable affording, in which this precision landing drone felt more interesting than others, and is far more affordable than the alternatives.

## Design (So far):
<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/c760f96e-b4cb-4be7-a97d-9bd38fc56c7e" />
If you haven't already noticed, this is by no means a final design, before I add the other parts of the BOM to the CAD, I want to first finalize all the parts I plan on purchasing so ensure compatibility so I'm not wasting my time and money. I was able to find these open source designs for the 450 mm frame I plan on purchasing as well as the SpeedyBee, and now simply need to design a plate adapter for the SpeedyBee and later 3d print it when the all parts are finalized and ordered. However, once the parts are finalized I can truly begin on the full design process.

# BOM (As of 7/13/26)
### 1. Structure & Propulsion

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| HAWK'S WORK F450 Drone Frame, 450mm Wheelbase Quadcopter Frame Kit with Landing Skid Gear (Pre-soldered) | 1 | $28.99 | [Link](https://www.amazon.com/dp/B09YQ4TM88) |
| Readytosky 2212 920KV Brushless Motors CW CCW for F330 F450 F550 S500 S550 X525 DJI Phantom Quadcopter(4PCS) | 1 | $39.99 | [Link](https://www.amazon.com/dp/B075DD16LK) |
| SoloGood 1045 (10x4.5) Propellers. 16 Pieces(8CW, 8CCW) Red & Black 10 inch FPV Props for F450 F550 S550 S500 FPV Quadcopter Multirotor | 1 | $13.99 | [Link](https://www.amazon.com/dp/B091KGR9Z6) |
| **Subtotal:** | | **$82.97** | |

### 2. Avionics & Control (The "Brain")

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| SpeedyBee F405 V5 OX32 55A 30x30 Model Aircraft FC&ESC Stack | 1 | $93.99 | [Link](https://www.speedybee.com/speedybee-f405-v5-55a-stack/) |
| Deegoo-FPV GPS Compass Module+ NEO-M8N+ GPS BDS Module Precision APM Drone Control GPS Receiver FPV Flight Control Pixhawk Navigation Module for APM PIX PX4, Compatible with APM Port I2C MWC | 1 | $28.99 | [Link](https://www.amazon.com/dp/B08NY9JSZ3) |
| FLYSKY FS-i6X 10CH 2.4GHz RC Transmitter Controller with FS-iA6B Receiver Upgrade Cable for RC Boat Racing Drone (Mode_2) | 1 | $58.48 | [Link](https://www.amazon.com/dp/B07Z8VCB45) |
| **Subtotal:** | | **$181.46** | |

### 3. Companion Computer & Precision Landing (Custom Logic)

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| Raspberry Pi 4 2GB Model B | 1 | $55.00 | [Link](https://www.canakit.com/raspberry-pi-4-2gb.html?cid=usd&src=raspberrypi) |
| Arducam for Raspberry Pi Camera Module 60fps Global Shutter 1.58MP IMX296 Camera with M12 Lens Equipped with 15-22pin FPC Flexible Cable for Raspberry Pi 5, 3, 4 A/B | 1 | $64.99 | [Link](https://www.amazon.com/dp/B0C3VGMTRH) |
| 3pcs 15 Pin 30cm 50cm 100cm FFC Ribbon Flexible Flat Cable for Camera Pi Camera Cable Long Extension Flexible Ribbon Cable | 1 | $8.16 | [Link](https://www.amazon.com/dp/B07DNYM8KC) |
| **Subtotal:** | | **$128.15** | |

### 4. Power & Wiring Infrastructure

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| OVONIC 3S LiPo Battery 3000mAh 11.1V 130C RC Battery with XT60 Connector | 1 | $36.99 | [Link](https://www.amazon.com/dp/B00DF2BL8H1) |
| B6AC Balance Battery Charger, B6 AC 80W Lipo Battery Balance Charger 6A Discharger, RC Car Battery Charger for NiMH/NiCD/LiPo/Li-ion LiFePO4 | 1 | $33.99 | [Link](https://www.amazon.com/dp/B0F3BSLY3K) |
| 3pcs 24V/12V to 5V DC-DC Step Down Module 5A USB Power Converter for Arduino Raspberry Pi... | 1 | $9.99 | [Link](https://www.amazon.com/dp/B0FXWLB3XX) |
| 18 Gauge Electrical Wire with Heat Shrink Tubing, 18 Awg Red and Black Tinned Copper Electric Stranded Wire 0.82mm² for Automotive House LED Lamp, Flexible PVC High Temp(10M/32.8FT) | 1 | $11.99 | [Link](https://www.amazon.com/dp/B0G4JWWVH7) |
| Fermerry 28 AWG Stranded Wire Spool 5ft Each 6 Colors Flexible 28 Gauge Silicone Hook up Wire Kit Electrical Tinned Copper Wire | 1 | $8.29 | [Link](https://www.amazon.com/dp/B089CR4SDM) |
| **Subtotal:** | | **$109.26** | |

I have decided on these parts for my BOM as of now, they are most likely subject to change as I am currently seeking feedback from other communities such as Reddit and HackClub as well as researching forums regarding each part. 

# 7/14/26
## Day 4: Advice and sanity checking my selected parts - 4 Hours
### Battery and motor dilemma:
I have received some advice from users on reddits with a couple suggesting that I switch to a 4s battery, however, the only option that is within my budget is a 4s with 1550mAh rather than the current 3s' 3000mAh. This would cause data collection to be long and tedious with a smaller flight time per battery.

If I wanted a 4s battery with similar capacity as the 3s, I would be increasing my budget even more, however, if I don't and I im not happy with the 3s' performance, then I'd lose much more than if I had made the safer, more expensive choice.

With all this is mind I've decided to compromise with swapping my current motors for a set that are rated for 2s-6s batteries, that way if I'm not happy with the 3s or if it doesn't work, I can buy a 4s battery without having to worry about swapping the motors or propellors and dedicate that same 3s as an opportunity for a seperate, future project :)

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| DYS X2812 900KV Brushless Motors for 7-8 Inch FPV Drone Frame (4PCS) | 1 | $55.98 | [Link](https://www.amazon.com/X2812-900KV-Brushless-Quadcopter-Multirotor/dp/B0G3F2GZSR) |

### Radio debate:
Another user suggested I get a Radiomaster pocket ELRS, however, this is quite over-budget with the main upside being the modern ELRS technology rather than the FS-i6X's older technology. 

I looked into it and I personally think its an unnecessary upgrade if the primary benefit if only having ELRS for a much greater price tag

Not all hope on ELRS was lost yet, as a different user suggested a T8L Radiomaster controller, which I considered for a good 15 minutes and overall assumed that the screen on the FS-i6x was a focal selling point along with its outer antenna providing a better signal.

<img width="547" height="267" alt="image" src="https://github.com/user-attachments/assets/bac951ea-79f7-42a0-a45b-57789f5bb3dd" />

(T8L - $35 for controller, ~$60 for all parts | FS-i6x - ~$59 for controller + receiver)


I referred back to the user and was informed that he never had an issue with signal and precisely the reason he suggests ELRS, but it didn't quite sway my decision entirely until I considered the weight of the receiver that the FS-i6x comes with. It would be another 15g on my already heavy drone which is operating on an already possibly underpowered 3s.

If I get the T8L, I can get an XR1 receiver weighing in at only 2 grams, and it is essentially the same price total to get the T8L, receiver, and batteries, as just getting the FS-i6x. In the grand scheme of things, it's an upgrade that I should and will buy now.

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| T8L Radio Controller (M2) | 1 | $34.99 | [Link](https://radiomasterrc.com/products/t8l-radio-controller?variant=47089026465984) |
| XR1 Nano Multi-Frequency ExpressLRS Receiver (2.4 GHz) | 1 | $11.99 | [Link](https://radiomasterrc.com/products/xr1-nano-multi-frequency-expresslrs-receiver?variant=46486320480448) |
| 18650 3200mAh 3.7V Battery (2pcs) for TX16S / Boxer / TX12/ Pocket / MT12 Radios | 1 | $11.99 | [Link](https://radiomasterrc.com/products/18650-3200mah-3-7v-battery-2pcs-for-tx16s-boxer-tx12-mt12-radios) |
| **Total:** | | **$58.97** | |


yes i will design the plate today, yes i will add that to the journal today, yes i will logs the hours for today, so far ive done 2 hrs, Yes a 130 c rated battery is a bit much and will try to downscale so im not paying too much, yes i will write abt the lengths of the ribbon wire and why its a pack of 3, and yes i will look for 1 step down motor instead of 3, most amazon links come in 3's tho...
