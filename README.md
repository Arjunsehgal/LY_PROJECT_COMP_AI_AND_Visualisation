
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
         1.

![App Screenshot](https://user-images.githubusercontent.com/59222712/141791449-4b6f3a17-938c-442f-a1ab-192d5aea20f7.JPG )

    b. vehicle :

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    c. raspberry pi 3B+ model
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

    d. raspberry pi camera :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
 
    e. arduino uno :
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

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

Insert gif or link to demo


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Documentation

[Documentation](https://linktodocumentation)


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

