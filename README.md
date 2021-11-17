
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

# LY_PROJECT_COMP_AI_AND_Visualisation
                                                         AUTONOMOUS SELF DRIVING CAR
                                                                      BY 
                                                                      AJAY BHAN &
                                                                      ARJUN SEHGAL
                                                         KJ SOMAIYA COLLEGE OF ENGINEERING


**TABLE OF CONTENTS.** 

    1.Introduction........................                                                                                                                                    
      1.1 Purpose.........................                                                                                                                        
      1.2 Scope...........................                                                                                                                      
      1.3 References......................                                                                                                                       

    2.Product Perspective.................                                                                                                                                
      2.1 Algorithm & Functions...........                                                                                                          
      2.2 Operational Environment.........                                                                                                                        



# 1. BACKGROUND :                                                                                                                                                                     
    Autonomous vehicles are automobiles that can move without any intervention by detecting the road, traffic flow and surrounding objects with the help of the control system they have. 
    These vehicles can detect objects around them by using technologies and techniques such as RADAR, LIDAR, GPS, Odometry, Computer Vision. The autopilot drive of autonomous vehicles starts briefly with the ultrasonic sensors on its wheels, detecting the positions of vehicles that are braking or parked, and data from a wide range of sensors are analysed with a central computer system. This event can only be described as a beginning. As the computer technologies are more accessible and cheaper the future of driverless cars becomes more achievable. Though still in its infancy, self-driving technology is becoming increasingly common and could radically transform our transportation system (and by extension, our economy and society).
    The automotive industry is experiencing a paradigm shift from conventional, human-driven vehicles into self-driving, artificial intelligence-powered vehicles. Self-driving vehicles offer a safe, efficient, and cost-effective solution that will dramatically redefine the future of human mobility. Self-driving cars have rapidly become one of the most transformative technologies to emerge. Fuelled, by Deep Learning algorithms, they are continuously driving our society forward and creating new opportunities in the mobility sector.

# 1.1 SCOPE :
    Our system will include:                                                                                                                                          
          • Lane detecting and following
          • Object recognition                                                                                                                                   
          • Stop Sign Detection                                                                                                                          
          • Traffic Signs Detection

# 1.2 PROJECT OBJECTIVE :

    • Road safety has been an issue for as long as cars have been in existence. Over 1.3 million people die of road accidents every year across the globe, most of which are preventable. 

    • Ever-rising Road traffic has led to an exponential increase in commute time. This has a direct impact not only on people's productivity but also on the environment.

    • Recent developments in machine learning and artificial intelligence along with the ever-increasing performance of modern-day computers have enabled the use of these technologies in developing self-driving cars. 

    These cars have several advantages, as described below:

          1. Better road safety: Machines are not prone to human-error and distractions, leading to swift and appropriate responses in real-time road conditions.

          2. Increased productivity: Reduced commute times mean more time can be spent on what matters more.

          3. Reduced expenditure: Reduction in accidents will directly lead to reduced expenditure on damages.

          4. Environment-friendly: Efficient driving styles of the self-driving car will lead to lower emissions.

          5. Better traffic discipline: Better law enforcement can be achieved and traffic can be managed by capping speed in various regions.


# 1.3 REFERENCES :
    1. Artificial Intelligence based Self-Driving Car
https://ieeexplore.ieee.org/document/9315223


    2. A Survey of Autonomous Driving: Common Practices and Emerging Technologies

https://ieeexplore.ieee.org/document/9046805 



    3. IoT based Self Driving Car

https://www.irjet.net/archives/V7/i3/IRJET-V7I31037.pdf 


    4. AN INTRODUCTION OF AUTONOMOUS VEHICLES AND A BRIEF SURVEY                                                                                                               
http://www.jcreview.com/fulltext/197-1593069401.pdf 


# 2. PRODUCT PRESPECTIVE
    ● The IOT based Car will be developed using Deep learning, Open CV and C++
    ● Each of the features will be developed individually according to the timeline which is decided.
    ● The Independent hardware modules will be built first and then all the dependent modules will be built.
    ● Deep learning will be used for implementing and predicting the Lane Detection, Object Detection, Stop Sign and Traffic Lights.

# 2.1 ALGORITHMS AND FUNCTIONS :
    • Convolutional Neural Network will be used for image processing to detect lane, stop and traffic signs.
    • Raspberry PI and Arduino UNO to work on master slave operations.

# 2.2 OPERATING ENVIORNMENT :
    ● Operating system - Windows 10 OS with C++ is needed.
    ● Platform – Raspberry PI desktop Imager 

#  a. SOFTWARE TOOLS : -
    o Arduino 1.8.16
    o Advanced IP Scanner
    o Balena Etcher
    o Disk Manager 
    o PUTTY
    o Vnc Viewer


# b. HARDWARE :
    o Raspberry PI 3B+
    o Arduino UNO
    o L298N Bridge
    o Raspberry PI Camera

# 3. DESIGN AND IMPLEMENTATION CONSTRAINTS :


# 3.1 USER DOCUMENTATION :
    o User manuals, on-line help, and tutorials will be delivered along with the software.
    o Video tutorials will help users with getting started and exploring all project features.



# 3.2 HARDWARE INTERFACES :
    a. Arduino UNO will be used for Forward/Backward &    Left/Right movement for vehicle.
    b. Raspberry PI 3B+ will be used to connect our pc through WIFI/Ethernet.
    c. L298N Bridge will control the motors.
 

# 3.3 SOFTWARE INTERFACES :
    a. Image processing using Open CV & C++ to find Lanes from Track.
    b. Using C++ code to capture images and videos.
    c. Deep learning will be used for implementing and predicting the Lane Detection, Object Detection, Stop Sign and Traffic Lights.


# ASSUMPTIONS :
    a. The main assumption in this project is that the system works well when there are no environmental factors. (Bad weather, holes, slope, etc.)
    b. Lane markings are assumed to be distinct. 
    c. For Obstacle Detection, we are considering no traffic and vehicle will overtake only from right.
    d. In our system, it is assumed that all traffic signs and the presence of all objects around the vehicle can be clearly seen. 
    e. It is assumed that all system elements are operating properly and there are no abnormal conditions. 

## SPECIFICATIONS(*information of components*) :

# Hardware Components :
   
    a. motor :
        1. Low density: lightweight, low inertia.
        2. Capability to absorb shock and vibration as a result of elastic compliance.
        3. Ability to operate with minimum or no lubrication, due to inherent lubricity.
        4. The relatively low coefficient of friction.
        5. Operating Voltage(VDC): 3~6 v (DC)
        6. Shaft Length (mm): 10mm
        7. Shaft Diameter (mm): 6mm (Double D-type)
        8. No Load Current: 40-180mA. 
        9. Load current: 170mA (when it is 4.5V)
        9. Rated Speed(After Reduction): 100 RPM
        10. Rated Torque: 0.8 Kg.cm
        11. Gear Ratio: 1:48
        12. No-load speed(5V): about 208RPM @ 5 volts
        14. Size: 70 x 23  x 18 mm
        15. Weight:28g

        specification :
    1. The 100 RPM Dual Shaft BO Motor Plastic Gear Motor – BO series straight motor gives good torque and rpm at lower operating voltages, which is the biggest advantage of these motors.
    2. Small shaft with matching wheels gives an optimized design for your application or robot. Mounting holes on the body & light weight makes it suitable for in-circuit placement. 
    3. This motor can be used with 69mm Diameter Wheel for Plastic Gear Motors and 87mm Diameter Multipurpose Wheel for Plastic Gear Motors.
    4. Low-cost geared DC Motor. It is an alternative to our metal gear DC motors. It comes with an operating voltage of 3-12V and is perfect for building small and medium robots.
    5. The motor is ideal for DIY enthusiasts. This motor set is inexpensive, small, easy to install, and ideally suited for use in a mobile robot car. They are commonly used in our 2WD platforms
          
    
    | SPECIFICATION                       | OF UNITS
    ------------------------------------------------
    | Operating Voltage (VDC)	      | 3 ~ 6
    | Shaft Length (mm)	              | 10
    | Shaft Diameter (mm)|(Double D-type) | 6
    | No Load Current (mA)	              | 40-180mA.
    | Rated Speed After Reduction (RPM)   |	100
    | Rated Torque (Kg-Cm)	              | 0.8
    | Weight (gm)	                      | 30
    | Dimensions in mm (LxWxH)	      | 70 x 23 x 19
    | Gearbox Shape	                      | Straight
    | Shipment Weight	              | 0.033 kg
    | Shipment Dimensions	              | 8 × 4 × 4 cm
    
        Features :
      1. Cost-effectiveness of the injection-molding process.
      2. Elimination of machining operations.
      3. Low density: lightweight, low inertia.
      4. Uniformity of parts.
      5. Capability to absorb shock and vibration as a result of elastic compliance.
      6. Ability to operate with minimum or no lubrication, due to inherent lubricity.
      7. The relatively low coefficient of friction.
      8. Corrosion-resistance; elimination of plating, or protective coatings.
      9. The quietness of operation.
      10. Tolerances often less critical than for metal gears, due in part to their greater resilience.
      11. Consistency with the trend to greater use of plastic housings and other components.
      
      b. Wheel :
        1. Loading Capacity: Max 2.5Kg
        2. Double D-hole For BO Motor: 6 mm
        3. Weight: 34g
        4. Wheel Diameter: 65 mm
        5. Color: Black (Tyre), Yellow (Rim)
        6. Wheel width: 27 mm
        7. Body Material: Plastic
        8. Grip Material: Rubber
        
    | SPECIFICATION OF WHEEL           | IN UNITS 
    -----------------------------------------------
    | Color	                           | Black (Tyre) && Yellow (Rim)
    | Internal Diameter(ID)(mm)	   | 51
    | Load Capacity(Kg/Wheel)	   | 2.5
    | Tyre Grip Material	           | Rubber
    | Wheel Body Material	           | Plastic
    | Wheel Diameter(mm)	           | 65
    | Wheel Width (mm)	           | 27
    | Weight(gm)	                   | 34 (each)
    | Shipment Weight	           | 0.4 kg
    | Shipment Dimensions	           | 30 × 18 × 5 cm
      
  <p align="center">
  <kbd>
  <img src="https://github.com/Arjunsehgal/LY_PROJECT_COMP_AI_AND_Visualisation/blob/master/images/motor%20and%20wheel.JPG" width="600" height= "400" style="border: 1px solid      black" />
    </kbd>
   </p>
   
    b. vehicle :
       1. Very handy and simple in assembling/disassembling.
       2. Strong components so as to withstand extreme terrain conditions.
       3. ransparent Car Chassis.
       4. Attractive design.

       specification :
    1. This is a Longer version of 4 wd double-layer smart car chassis. 
    2. It comes with the four pairs of Geared Motors and Wheels. 
    3. All the products included in this car kit are quality products. 
    4. The chassis used in this kit is transparent to create dynamic handling of the components mounted on your robotic vehicle.

       Features :
       1. Very handy and simple in assembling/disassembling.
       2. Strong components to withstand extreme terrain conditions.
       3. Transparent Car Chassis.
       4. Attractive design.
       5. Double-layer structure, much of mounting holes, enough space
       6. Easy to install a variety of control panels, sensors
       7. Educational toys, Ideal for the DIY platform

<p align="center">
  <kbd>
  <img src="https://github.com/Arjunsehgal/LY_PROJECT_COMP_AI_AND_Visualisation/blob/master/images/vehicle.JPG" width="600" height= "400" style="border: 1px solid      black" />
    </kbd>
   </p>

    c. raspberry pi 3B+ model :
       1. 64-bit SoC @ 1.4GHz
       2. 1GB LPDDR2 SDRAM
       3. 2.4GHz and 5GHz IEEE 802.11.b/g/n/ac wireless LAN, Bluetooth 4.2, BLE
       4. Gigabit Ethernet over USB 2.0 (maximum throughput of 300 Mbps)
       5. Extended 40-pin GPIO header, Full-size HDMI
       6. 4 USB 2.0 ports
       7. CSI camera port, DSI display port for connecting a Raspberry Pi touchscreen display
       8. 4-pole stereo output and composite video port

       specification : 
    1. The Raspberry Pi 3 Model B+ is the latest product in the Raspberry Pi 3 range, boasting a 64-bit quad-core processor running at 1.4GHz, dual-band 2.4GHz, and 5GHz wireless LAN, Bluetooth 4.2/BLE, faster Ethernet, and PoE capability via a separate PoE HAT.
    2. The secret sauce that makes this computer so small and powerful is the Broadcom BCM2837, an ARM Cortex-A53 64-bit Quad-Core Processor System-on-Chip operating at 1.4GHz. 
       The GPU provides OpenGL ES 2.0, hardware-accelerated OpenVG and 1080p30 H.264 high-profile decode. 
       It is capable of 1Gpixel/s, 1.5Gtexel/s or 24 GFLOPs of a general-purpose computer. It means that if you plug the Raspberry Pi 3 B+ into your HDTV, you could watch Blu-ray quality video, using H.264 at 40MBits/s.
    3. The Raspberry Pi 3 B+ has four built-in USB ports that provide enough connectivity for a mouse, keyboard or anything else that you feel the RPi needs. 
       But if you want to add even more, you can still use a USB hub. Keep in mind, it is recommended that you use a powered hub so as not to overtax the onboard voltage regulator. 
       Powering the Raspberry Pi 3 B+ is easy just plug and Play with 5V/2.5A USB power supply into the micro USB port. 
       There’s no power button, so the RPi will begin to boot as soon as power is applied. To turn it off, simply shut down the Pi 3 B+, then remove power. 
       The four built-in USB ports can even output up to 1.2A, enabling you to connect more power-hungry USB devices.
     
    | SPECIFICATION OF MODEL  
    ------------------------------------------------------------   
    | Model	                           | Raspberry Pi 3 Model B+
    | Processor	                   | Broadcom BCM2837B0, Cortex-A53 (ARMv8) 64-bit SoC @ 1.4GHz
    | RAM	                           | 1GB LPDDR2
    | Connectivity	                   | Gigabit Ethernet over USB 2.0
    | Operating Power	           | 5V/2.5A DC
    | GPIO	                           | Standard 40-pin GPIO Header
    | Video and Sound	           | 2-Lane MIPI DSI Display Port
    | Clock Speed	                   | 1.4 GHz
    |On Board Ports	                   | 15-pin MIPI Camera Serial Interface (CSI-2)
                                       | 4 x USB 2.0 Connector
                                       | 4-pole stereo output and composite video port
                                       | 40-pin 2.54 mm (2×20 strip) GPIO
                                       | Full-size HDMI Output Port
    | Micro-SD Card Slot	           | Yes (FAT32 format), support maximum 32G Micro SD Card
    | Operating Temperature Range (°C) | -10 to 60
    | Weight (gm)	                   | 44
    | Length (mm)	                   | 85
    | Width (mm)	                   | 56
    | Height (mm)	                   | 23
    | HDMI Port	                   | Full Size
    | Shipment Weight	           | 0.047 kg
    | Shipment Dimensions	           | 9 × 6 × 4 cm
    
      Features :
        1. 64-bit SoC @ 1.4GHz
        2. 1GB LPDDR2 SDRAM
        3. 2.4GHz and 5GHz IEEE 802.11.b/g/n/ac wireless LAN, Bluetooth 4.2, BLE
        4. Gigabit Ethernet over USB 2.0 (maximum throughput of 300 Mbps)
        5. Extended 40-pin GPIO header
        6. Full-size HDMI
        7. 4 USB 2.0 ports
        8. CSI camera port for connecting a Raspberry Pi camera
        9. DSI display port for connecting a Raspberry Pi touchscreen display
        10. 4-pole stereo output and composite video port
        11. Micro SD port for loading your operating system and storing data
        12. 5V/2.5A DC power input
        13. Power-over-Ethernet (PoE) support (requires separate PoE HAT)

      USEFUL LINKS : Read below the documentation part
       
<p align="center">
  <kbd>
  <img src="https://github.com/Arjunsehgal/LY_PROJECT_COMP_AI_AND_Visualisation/blob/master/images/raspberrypi.jpg" width="600" height= "400" style="border: 1px solid      black" />
    </kbd>
   </p>
   
   <p align="center">
  <kbd>
    <img src="https://projects-static.raspberrypi.org/projects/raspberry-pi-setting-up/0d6033edf45ad2d4185ed05d6cd9a01e2f803034/en/images/pi-plug-in.gif" width="600" height= "400" />
    </kbd>
   </p>

    d. raspberry pi camera :
        1. Resolution: 5 MP
        2. Interface Type: CSI(Camera Serial Interface)
        3. Dimensions: 25x23x8 (LxWxH) mm
        4. Supported Video Formats: 1080p @ 30fps, 720p @ 60fps and 640x480p 60/90 video
        5. Fully Compatible with Raspberry Pi 3 and 4 Model B
        6. Plug-n-Play camera for Raspberry Pi 3 and 4 Model B.

        Specification :
    1. The 5MP Raspberry Pi 3/4 Model B Camera Module Rev 1.3 with Cable equips flexible cable for attaching with Raspberry Pi 3 Model B. 
       The 5MP camera module is perfect for small Raspberry Pi projects which have very little space allowance just boot up the latest version of Raspbian and you are good to go.
    2. The high-definition 5MP camera delivers outstanding photos but can also shoot video, ideal for drones or a CCTV project. 
       The lightweight camera board allows for it is useful in more practical roles, such as a hidden camera, even a camera for a Pi-phone.
    3. This Raspberry Pi Camera Module is a custom designed add-on for Raspberry Pi. It attaches to Raspberry Pi by way of one of the two small sockets on the board upper surface. 
       This interface uses the dedicated CSI interface, therefore it is designed especially for interfacing to cameras. 
       The CSI bus is capable of extremely high data rates, and it exclusively carries pixel data.
    4. No adapters required.This camera will plug directly into the Raspberry Pi 3 Model B camera port.
       
       Hardware connection: 
    1. Soft cable, 90-degree vertical connector, HDMI port next to it. When connecting the contact side facing the HDMI interface.
    2. Tear protective film on the lens
    3. Bare boards, pay attention to ESD damage, beware of static electricity!

       Software: 
    1. RPi firmware and raspi-config has been updated to the camera, do an apt-get update; apt-get upgrade;
    2. Raspi-config, select the camera, start RPi firmware camera driver, and then restart
    3. Using the command-line program raspivid and raspistill operate a camera to capture video clips or images
    4. To capture video clips need to play with MPlayer

    | SPECIFICATION OF CAMERA     | IN UNITS 
    ------------------------------------
    | Resolution	              | 5 MP
    | Compatibility	              | Raspberry Pi 3B+/4B
    | Lens Focus	              | Fixed Focus
    | Image Size(Pixels)	      | 2592Ã—1944
    | Interface Type	      | CSI(Camera Serial Interface)
    | Sensors	              | Omnivision 5647 fixed-focus
    | Aperture	              | 2.9
    | Focal Length	              | 3.29
    | FOV	                      | 72.4Â°
    | Length (mm)	              | 25
    | Width (mm)	              | 23
    | Height (mm)	              | 8
    | Weight (gm)	              | 3
    | Shipment Weight	      | 0.005 kg
    | Shipment Dimensions	      | 12 × 5 × 3 cm

       Features :
    1. Supported Video Formats: 1080p @ 30fps, 720p @ 60fps and 640x480p 60/90 video
    2. Fully Compatible with Raspberry Pi 3 and 4Model B.
    3. Small and lightweight camera module.
    4. Plug-n-Play camera for Raspberry Pi 3 and 4 Model B.
       
<p align="center">
  <kbd>
  <img src="https://github.com/Arjunsehgal/LY_PROJECT_COMP_AI_AND_Visualisation/blob/master/images/raspberry-pi-camera.jpg" width="600" height= "400" style="border: 1px solid      black" />
    </kbd>
   </p>
 
    e. arduino uno :
        1. A basic Arduino Kit including everything to get started.
        2. It includes a quality proven Arduino Cable.
        3. It includes a strong and sturdy Transparent Acrylic Case.
        4. Microcontroller ATmega328 (SMD) – Interface CH340G
        5. Operating Voltage: 5V
        6. Input Voltage (recommended): 7-12V
        7. Digital I / O Pins 14 (of which 6 provide PWM output)
        8. Analog Input Pins: 6
      
      Specifications :
    1. This is UNO R3 CH340G ATMega328P compatible with Arduino + Cable + Transparent Acrylic Case For Uno R3. 
       A basic Arduino kit with all the components included eliminating the time our customers for finding and buying Arduino ant its basic accessories.
       Uno R3 CH340G ATmega328p Development Board is the low-cost version of the popular Uno R3 Arduino. 
       It is assembled with the CH340 USB to Serial converter chip, instead of using an Atmega16U2 chip.

    2. We have used plenty of these low-cost Arduino boards with CH340 chips, and have found them to work perfectly. 
       The only time the CH340 chip is used is during programming and when using the serial output of the USB port. During normal operation, this board is identical to the more expensive version without CH340 chip.

       
       How to use:
            1. Download the IDE Arduino

    Link: http://arduino.cc/en/Main/Software (Copy to open)

            2. Download the USB chip driver

    Link: http://www.5v.ru/zip/ch341ser.zip (Copy to open)

            3. Plug in UNO development board, the driver will be installed automatically

            4. Select the UNO from the die

            5. Select the COM port

            6. The best choice first, Arduino comes with routine procedures, burn into it.
        
    FEATURES :
    a. UNO R3 Arduino CH340G :

        1. Microcontroller ATmega328 (SMD) – Interface CH340G
        2. Operating Voltage: 5V
        3. Input Voltage (recommended): 7-12V
        4. Input Voltage (limits): 5-20V
        5. Digital I / O Pins 14 (of which 6 provide PWM output)
        6. Analog Input Pins: 6
        7. DC Current per I Pin: 40 mA
        8. DC Current for 3.3V Pin: 50 mA
        9. Flash Memory: 32 KB (ATmega328) of which 0.5 KB used by bootloader
        10. SRAM: 2 KB (ATmega328)
        11. EEPROM: 1 KB (ATmega328)
        12. Clock Speed: 16 MHz

    b. Cable for UNO Arduino:

        1. Length 1 foot
        2. Hot Pluggable.
        3. Fully compatible with the PC.
        4. Molded strain relief and PVC overmolding to ensure a lifetime of error-free data transmissions.
        5. Aluminum under-mold shield helps meet FCC requirements on KMI/RFI interference.
        6. Foil and braid shield complies with fully rated cable specifications reducing EMI/FRI interference.
        7. For Error-Free High-Performance Transmission.

    c. Transparent acrylic case:

        1. Weight: 53 gm.
        2. Dimensions : 79.5 x 64.5 x 21 mm.
        3. Material: A grade acrylic sheet.
        4. For UNO R3 Development Board only.
        5. With screw copper pillar and installation instructions.
        6. To protect your little computer against damages, dust and scratches Clear Top and Bottom.
        7. This case provides easy access to all ports.
        8. It requires no tools for easy assembly and disassembly.
        9. Simply Clicks Together Enclosure.
    
<p align="center">
  <kbd>
  <img src="https://github.com/Arjunsehgal/LY_PROJECT_COMP_AI_AND_Visualisation/blob/master/images/raspberry-pi-camera.jpg" width="600" height= "400" style="border: 1px solid      black" />
    </kbd>
   </p>

    f. L298n Bridge :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

# software Components :

    a. Arduino 1.8.16 :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    b. Advanced IP Scanner :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    c. Balena Etcher :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    d. Disk Manager :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    e. PuTTy :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    f. VNC viewer :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## SYSTEM ARCHIETECTURE :

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## DESIGN OF PROPOSED MODEL :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## FLOWCHART FOR ALGORITHMS :
# a. Lane Detection  :                                              
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

# b. Obstacle Detection :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

# c. Traffic Light Detection :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## FeatureS

|  UI  | Logic | Feature |
| ------ | ------ | ------|
| ✔ | ✔ | Teacher Login
| ✔ | ✔ | Student Login
| ✔ | ✔ | Parent Login
| ✔ | ✔ | Multiple Child Profile View
| ✔ | ✔ | Chat between teacher and parent
| ✔ | ✔ | Intro Screens.
| ✔ | ✔ | Post photo or notice on Standard post section(Only Teacher)
| ✔ | ✔ | Post photo or notice on global post section(Only Teacher)
| ✔ | ✔ | Dark Mode
| ✔ | ✔ | Profile Setup
| ✔ | ✔ | Forget Password
| ✔ |   | TimeTable
### and many more......

# Conclusion and Future Scope :

    The model which we proposed is likely to have a significant impact on automated driving technology, either by overcoming the weakness of previous methods or by proposing an alternative.

    Future Goals:
        Control Speed of Motors
        Traffic Detection 
        Parking Car System 
        Night Light Cameras
        Using Multiple Cameras

# Challenges :
    1. Incorrect and Improper connections will lead to failure of circuits.
    2. Low Quality Camera might be challenging while capturing the images at night. 
    3. Lack of knowledge in handling IOT devices.
    4. Heating Problems might be an another important challenge when system used for longer time.



## Acknowledgements :

 - [Arjunsehgal](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [ajaybhan44](https://github.com/matiassingers/awesome-readme)
 



## Authors

- [@Arjunsehgal](https://www.github.com/octokatherine)
- [@ajaybhan44](https://www.github.com/octokatherine)



## Contributing

Contributions are always welcome!

See `readme.md` for ways to get started.

Please adhere to this project's `code`.


## Demo

**1. INTRO TO RASPBERRY PI :** 
<div align="center">
  <a href="https://www.youtube.com/watch?v=NNwoqEybOqg"><img src="https://img.youtube.com/vi/NNwoqEybOqg/0.jpg" alt="Click Here TO Watch"></a>
</div>
 
## Deployment

To deploy this project run

```bash
  npm run deploy
```


# Documentation to get start with :

# 1. Raspberry Pi Model : 

a. [**Downloads from Raspberry Pi**](https://www.raspberrypi.com/software/)   
b. [**Setting up your Raspberry Pi**](https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up)     
c. [**Raspberry Pi Acessories**](https://robu.in/product-category/raspberry-pi/pi-accessories/)   
d. [**RASPBERRY PI 3 MODEL B+ PRODUCT BRIEF**](https://static.raspberrypi.org/files/product-briefs/Raspberry-Pi-Model-Bplus-Product-Brief.pdf)   
e. [**RASPBERRY PI 3 MODEL B+ SCHEMATIC DIAGRAMS**](https://datasheets.raspberrypi.com/rpi3/raspberry-pi-3-b-plus-reduced-schematics.pdf)

## RELATED ARTICLES TO DEEP DIVE:
 
a. [**BLINKING LED USING GPIO PINS OF RASPBERRYPI**](https://robu.in/blinking-led-using-gpio-pins-of-raspberrypi/)   
b. [**DEVELOPING SIMPLE GUI USING “TKINTER” TO CONTROL GPIO’S OF RASPBERRY PI**](https://robu.in/developing-simple-gui-using-tkinter-to-control-gpios-of-raspberry-pi/)   
c. [**INSTALLING ANY REQUIRED OS ON SD CARD FOR RASPBERRYI PI**](https://robu.in/installing-any-required-os-on-sd-card-for-raspberryi-pi/)   
d. [**USING PHONE/LAPTOP AS DISPLAY FOR RASPBERRY PI HEADLESS MODE**](https://robu.in/using-laptop-android-as-raspberry-pi-display/)


## FAQ

#### Question 1

Answer 1

#### Question 2

Answer 2


## Feedback

If you have any feedback, please reach out to us at   
arjun.sehgal@somaiya.edu   
ajay.bhan@somaiya.edu


## Roadmap

- Additional browser support

- Add more integrations

