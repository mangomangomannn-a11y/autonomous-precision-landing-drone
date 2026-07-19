# 7/11/26 - 7/13/26
## Days 1-3: Design, budget restriction influence, planning, researching, tad bit of CAD, 7/10/26 - 9 Hours
This is being written about 2 days late because I first had to learn the ropes of making my own github project and got more sidetracked on the drone itself rather than the neat setup of my github.
I've had the intent of building a drone with something special in its design for about 4 months but never got started due to school sidetracking me. 

(Future) This journal covers most of my decision making and why I made them, I had fun writing it all and hope you enjoy reading it.

However, once summer started, I couldn't decide what I wanted to build. I considered generative drone frame design, UAV based autonomous flight, however, I ultimately decided on a autonomous precision landing drone for two main reasons: For one, as an aspiring astronautical engineer, it is a similar "control" type of technology used in the Mars 2020 Perseverance Rover to autonomously identify landing targets, as well as in SpaceX's Falcon 9 landings. But an arguably more notable factor was budget. I needed a project that I could feel more comfortable affording, in which this precision landing drone felt more interesting than others, and is far more affordable than the alternatives.

## Design (So far):
<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/c760f96e-b4cb-4be7-a97d-9bd38fc56c7e" />
If you haven't already noticed, this is by no means a final design, before I add the other parts of the BOM to the CAD, I want to first finalize all the parts I plan on purchasing so ensure compatibility so I'm not wasting my time and money. I was able to find these open source designs for the 450 mm frame I plan on purchasing as well as the SpeedyBee, and now simply need to design a plate adapter for the SpeedyBee and later 3d print it when the all parts are finalized and ordered. However, once the parts are finalized I can truly begin on the full design process.

# BOM (As of 7/13/26)
### 1. Structure + Propulsion

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| HAWK'S WORK F450 Drone Frame, 450mm Wheelbase Quadcopter Frame Kit with Landing Skid Gear (Pre-soldered) | 1 | $28.99 | [Link](https://www.amazon.com/dp/B09YQ4TM88) |
| Readytosky 2212 920KV Brushless Motors CW CCW for F330 F450 F550 S500 S550 X525 DJI Phantom Quadcopter(4PCS) | 1 | $39.99 | [Link](https://www.amazon.com/dp/B075DD16LK) |
| SoloGood 1045 (10x4.5) Propellers. 16 Pieces(8CW, 8CCW) Red & Black 10 inch FPV Props for F450 F550 S550 S500 FPV Quadcopter Multirotor | 1 | $13.99 | [Link](https://www.amazon.com/dp/B091KGR9Z6) |
| **Subtotal:** | | **$82.97** | |

### 2. Brain/Electronics

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| SpeedyBee F405 V5 OX32 55A 30x30 Model Aircraft FC&ESC Stack | 1 | $93.99 | [Link](https://www.speedybee.com/speedybee-f405-v5-55a-stack/) |
| Deegoo-FPV GPS Compass Module+ NEO-M8N+ GPS BDS Module Precision APM Drone Control GPS Receiver FPV Flight Control Pixhawk Navigation Module for APM PIX PX4, Compatible with APM Port I2C MWC | 1 | $28.99 | [Link](https://www.amazon.com/dp/B08NY9JSZ3) |
| FLYSKY FS-i6X 10CH 2.4GHz RC Transmitter Controller with FS-iA6B Receiver Upgrade Cable for RC Boat Racing Drone (Mode_2) | 1 | $58.48 | [Link](https://www.amazon.com/dp/B07Z8VCB45) |
| **Subtotal:** | | **$181.46** | |

### 3. Pi + Precision Landing

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| Raspberry Pi 4 2GB Model B | 1 | $55.00 | [Link](https://www.canakit.com/raspberry-pi-4-2gb.html?cid=usd&src=raspberrypi) |
| SanDisk 32GB Ultra® microSDHC 120MB/s A1 Class 10 UHS-I | 1 | $22.59 | [Link](https://www.amazon.com/dp/B08L5HMJVW) |
| Arducam for Raspberry Pi Camera Module 60fps Global Shutter 1.58MP IMX296 Camera with M12 Lens Equipped with 15-22pin FPC Flexible Cable for Raspberry Pi 5, 3, 4 A/B | 1 | $64.99 | [Link](https://www.amazon.com/dp/B0C3VGMTRH) |
| 3pcs 15 Pin 30cm 50cm 100cm FFC Ribbon Flexible Flat Cable for Camera Pi Camera Cable Long Extension Flexible Ribbon Cable | 1 | $8.16 | [Link](https://www.amazon.com/dp/B07DNYM8KC) |
| **Subtotal:** | | **$128.15** | |

### 4. Power/Wiring

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| OVONIC 3S LiPo Battery 3000mAh 11.1V 130C RC Battery with XT60 Connector | 1 | $36.99 | [Link](https://www.amazon.com/dp/B00DF2BL8H1) |
| B6AC Balance Battery Charger, B6 AC 80W Lipo Battery Balance Charger 6A Discharger, RC Car Battery Charger for NiMH/NiCD/LiPo/Li-ion LiFePO4 | 1 | $33.99 | [Link](https://www.amazon.com/dp/B0F3BSLY3K) |
| 3pcs 24V/12V to 5V DC-DC Step Down Module 5A USB Power Converter for Arduino Raspberry Pi... | 1 | $9.99 | [Link](https://www.amazon.com/dp/B0FXWLB3XX) |
| 18 Gauge Electrical Wire with Heat Shrink Tubing, 18 Awg Red and Black Tinned Copper Electric Stranded Wire 0.82mm² for Automotive House LED Lamp, Flexible PVC High Temp(10M/32.8FT) | 1 | $11.99 | [Link](https://www.amazon.com/dp/B0G4JWWVH7) |
| Fermerry 28 AWG Stranded Wire Spool 5ft Each 6 Colors Flexible 28 Gauge Silicone Hook up Wire Kit Electrical Tinned Copper Wire | 1 | $8.29 | [Link](https://www.amazon.com/dp/B089CR4SDM) |
| **Subtotal:** | | **$109.26** | |

I have decided on these parts for my BOM as of now, they are most likely subject to change as I am currently seeking feedback from other communities such as Reddit, Discord and HackClub as well as researching forums regarding each part. 

# 7/14/26
## Day 4: Advice and sanity checking my selected parts - 4 Hours
### Battery and motor dilemma:
I have received some advice from users on reddits with a couple suggesting that I switch to a 4s battery, however, the only option that is within my budget is a 4s with 1550mAh rather than the current 3s' 3000mAh. This would cause data collection to be long and tedious with a smaller flight time per battery.

If I wanted a 4s battery with similar capacity as the 3s, I would be increasing my budget even more, however, if I don't and I im not happy with the 3s' performance, then I'd lose much more than if I had made the safer, more expensive choice.

With all this is mind I've decided to compromise with swapping my current motors for a set that are rated for 2s-6s batteries, that way if I'm not happy with the 3s or if it doesn't work, I can buy a 4s battery without having to worry about swapping the motors or propellors and dedicate that same 3s as an opportunity for a seperate, future project :)

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| DYS X2812 900KV Brushless Motors for 7-8 Inch FPV Drone Frame (4PCS) | 1 | $55.98 | [Link](https://www.amazon.com/X2812-900KV-Brushless-Quadcopter-Multirotor/dp/B0G3F2GZSR) |

It's true these motors are ideally rated for 7-9 inch props, with the 3s battery I plan on using, the 10 inch props are a better choice to generate sufficient thrust

They also weigh ~52 grams more, which looks like alot, but is only ~4% (probably ~6% because of my extra electronic components) of the total weight of a 450mm drone, which isn't much.

### Radio debate:
Another user suggested I get a Radiomaster pocket ELRS, however, this is quite over-budget with the main upside being the modern ELRS technology rather than the FS-i6X's older technology. 

I looked into it and I personally think its an unnecessary upgrade if the primary benefit if only having ELRS for a much greater price tag

Not all hope on ELRS was lost yet, as a different user suggested I get a Radiomaster Pocket *Crush* (Essentially just the pocket but different solid color options for a lower price)

<img width="545" height="270" alt="image" src="https://github.com/user-attachments/assets/ba57296a-7110-4a0c-8976-58cdac09961a" />

(Pocket Crush - $65 for controller, ~$90 for all parts | FS-i6x - ~$59 for controller + receiver)

I referred back to the user and was informed that he never had an issue with signal and precisely the reason he suggests ELRS, but it didn't quite sway my decision entirely until I considered the weight of the receiver that the FS-i6x comes with. It would be another 15g on my already heavy drone which is operating on an already possibly underpowered 3s. If I get the Pocket Crush, I can get an XR1 receiver weighing in at only 2 grams.

If that wasn't reason enough, I asked a discord server with many knowledgeable builders and all of them suggest the pocket and gave so many real issues with the FS-i6x, especially in this modern age.

Just look at this:

<img width="432" height="394" alt="image" src="https://github.com/user-attachments/assets/3d46d25c-670a-4b65-ae4b-b8773c9c53f6" />


And so, with all that reasoning from Reddit and Discord, I've decided to swap to the Pocket Crush.

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| Pocket Crush Radio Controller (M2) | 1 | $64.99 | [Link](https://radiomasterrc.com/products/pocket-crush-radio-controller) |
| XR1 Nano Multi-Frequency ExpressLRS Receiver (2.4 GHz) | 1 | $11.99 | [Link](https://radiomasterrc.com/products/xr1-nano-multi-frequency-expresslrs-receiver?variant=46486320480448) |
| 18650 3200mAh 3.7V Battery (2pcs) for TX16S / Boxer / TX12/ Pocket / MT12 Radios | 1 | $11.99 | [Link](https://radiomasterrc.com/products/18650-3200mah-3-7v-battery-2pcs-for-tx16s-boxer-tx12-mt12-radios) |
| **Total:** | | **$88.97** | |

# 7/15/2026
## Day 5: More advice, switching parts, calculating thrust, considering adaptor plate design - 4 Hours
The same user who suggested I get the other motor also mentioned a cheaper, yet more modern and higher performance compass:

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :---: |
| HGLRC M100 Pro GPS / QMC5883L Compass | 1 | $20.99 | [Link](https://www.amazon.com/dp/B0DPH8FV7K) |

It's a compatible compass that functions the same as the previous DeeGoo compass, but costs $8 less, weighs ~10 grams less, regularly gets 30+ satelites, and has almost twice the range.

Yeah, this was a no-brainer, I'm glad he told me about this compass.

### Thrust Calculation:
I went ahead and threw the specs into a trusted thrust calculator and the results came back looking pretty promising:

- At full throttle, each motor produces about 671 grams of thrust, giving me 2.68 kg of total lift
- Since the drone is gonna weigh from around 1.2-1.5 kg, I'll be getting roughly a 2:1 thrust to weight ratio (Meaning it can easily hover at half throttle and dedicate an ample amount of power to fight wind)
- It'll only draw about 200 Watts at max power, far below my ESC's maximum (Unlikely anything will overheat/burn up)

<img width="1016" height="906" alt="image" src="https://github.com/user-attachments/assets/ca08c785-dab6-4cf2-804b-bc8b8c8496f1" />


### The Adaptor Plate:
I was initially planning on fully designing the adaptor in Onshape, but I thought about how I would design it and I just can't seem to decide how I'm gonna do it.

I'm considering using the rectangular, thin center holes and making a part that has thin pieces that go through those holes and I screw them into eachother to secure and prevent it from being pulled up but I'm unsure of the reliability of that design aswell as just how secure it would really be...

<img width="1297" height="798" alt="image" src="https://github.com/user-attachments/assets/bcd21e42-5107-4f96-a46e-5c215b821004" />


This is a problem for tomorrow, it's getting late and I want to sleep.

# 7/16/26
## Day 6 - Design - 5 Hours

<img width="1313" height="787" alt="image" src="https://github.com/user-attachments/assets/8d25d98c-595f-4e84-a49e-7eebeec9e9af" />


This is the day's work, I searched for public STEP files on GrabCad, among other websites (no luck on those): Some designs weren't exectly what I'm purchasing, but still work just fine as their shapes are consistent (Arducam, 1045 Props, Motors) and I had to design the battery (It's just a simple rectangular prism).

I still need to design the adaptor plate and I even printed out a design of the base plate and carried it around with me all day (Not part of the 5 hours), thinking about how I would design this adaptor plate. A couple new ideas came to mind but they still haven't been finalized as I'm not 100% confident on the stacking orientation of the Pi and SpeedyBee.

I could put the Pi under the SpeedyBee stack, or vice versa. I could put the Pi on the very top plate, seperate from the stack. I could move the battery to the top and put the Pi under the whole thing. All are possibilities, I just need to make a decision to finalize the design. 

I'm afraid of putting the Pi on the top of bottom of the whole frame because it is an expensive component that would be far more likely to get broken if placed in either of those spots, but I'm also afraid of facing the difficulties involved with stacking the SpeedyBee and Pi in between the plates.

# 7/17/26
## Day 7 - Changing parts, making the drone legal: - 4 Hours

To legally fly a drone over 250g in the US, I need to pass an online test (Easy) for a certification, pay $5 for a registration marker from the FAA, and most notably, pay $40 on a Remote ID to attach to the drone to be tracked.

I found an offer from a trusted Aliexpress seller that contains the Radiomaster Pocket ELRS, XR1 reciever (2.4GHz), and the 2 18650 batteries that I need all for only ~$100. It saves me around $20-30 from alternatively buying the Pocket Crush among the other parts from the official Radiomaster site, due to shipping.

<img width="1669" height="576" alt="image" src="https://github.com/user-attachments/assets/0bf9f5ff-025b-4568-a437-a1aa1a579b9f" />



Despite my previous rant as to why I'm getting a 3s rather than a 4s, I'm planning on changing my mind for a multitude of reasons, the most notable being that my current motors are overkill and are unable to be downscaled to a smaller frame for alternative reuse. This entails buying a different set of motors that essentially require a 4s battery to provide enough propulsion for the 1.2kg-1.5kg frame, and this also requires 8045's as alternative motors are rated for 7-8 inch props.

I'm going to get these 4s batteries. I initially thought a downgrade from 3000mAh in my 3s to 2200mAh in a 4s was bad, but after doing the calculations:

3000mAh × 11.1V = 33.3 Wh
2200mAh × 14.8V = 32.5 Wh

The Watts per Hour for both, are virtually the same, less than a 3% difference between the two. On top of that, it's the same dimensions as the 3s.

| Item Name | Qty. | Price (total) USD | Item Link |
| :--- | :---: | :---: | :--- |
| OVONIC 4S LiPo Battery 2200mAh 14.8V 130C RC Battery with XT60 Connector | 1 | $45.99 | [Link](https://www.amazon.com/OVONIC-Battery-2200mAh-14-8V-Connector/dp/B0DF23MSJY/ref=ast_sto_dp_puis) |

Tomorrow I'm gonna decide on the motors and the props that go with them.

# 7/18/26
## Day 8 - Finalizing the part decisions, Starting the Plate Adaptor, Adding to & Adjusting the CAD - 8 Hours

I found reliable ReadyToSky 2212 Motors for a cheaper price than my previous DYS motors on amazon, aswell as good 8045 props to go with my motors:

| Item Name | Qty | Price | Link |
| :--- | :---: | :---: | :--- |
| **2212 920KV Brushless Motors CW CCW for F330 F450 F550 S500 S550 X525 DJI Phantom Quadcopter(4PCS)** | 1 | $39.99 | https://www.amazon.com/dp/B075DD16LK |
| **uxcell RC Propellers CW CCW 8045 8x4.5 Inch 2-Vane Fixed-Wing for Airplane Toy, Nylon Black 4 Pairs with Adapter Rings** | 1 | $17.39 | https://www.amazon.com/dp/B07PVGWH1N |

I adjusted the positioning of the components on the CAD, where the battery was moved to the top, and the Pi was moved to under the frame for easier access. This Pi, however, needed an adaptor plate for it to attach to, which will also act as the other half of the adaptor plate for the SpeedyBee.

<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/70dc805a-ba1d-4aa4-97c2-ce0cd9c52017" />


I designed this to include ventilation for the Pi, lined up screw hole dimensions, and extended tabs on the left and right side to reach into the holes in the frame, and give the SpeedyBee adaptor a surface to be secured onto. They will be secured to eachother and sandwiched between the bottom frame plate.

Along with this, I also finished up the majority of the CAD by adding and assembling the remaining components such as the Compass, the Remote ID, the XR1 Receiver, and different Motors and Props.

<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/838f34b0-338e-4e8f-9aa1-265e7cf77476" />


This is almost the finalized design, I just need to finish up the SpeedyBee plate adaptor tomorrow and finish it in assembly.

# 7/19/26
## Day 9 - 



yes i will design the plate today, yes i will add that to the journal today, yes i will update the bom
