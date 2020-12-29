# RoboTICK - OpenSource &amp; OpenHardware robotic free mobile platform (based on ROS)


## Introduction 
Few months ago I decided to build my own mobile robotic platform from scratch. I have a few motivators: understanding prototyping robots, building vehicle from CAD design to ready to use and learning new version of ROS. Of course future plans are: deploying Machine Learning models on platform, autonomous alghoritms, high availability on hardware and software levels by redundancy internal systems (power, computer, network, etc).

## Official idea presentation
Presentation from my [IoT, Hardware & Robotics meetup](https://www.meetup.com/pl-PL/Internet-of-Things-Hardware-Robotics-Pozna%C5%84/) about this project [Let's build a robot with ROS - Internet of Things, Hardware & Robotics meetup #1 Poznań](https://www.slideshare.net/bieli/lets-build-a-robot-with-ros-internet-of-things-hardware-robotics-meetup-1-pozna)


## Project structure - divide by specific stuff

### Domains:

- `vehicle_construction` - CAD construction, Bill of Materials, STL files for 3D printer
  - `frame`
  - `connections`
  - `motors`
  - `drive transfer`
  - `directions`
  - `depreciation`
- `hardware` - embedded computers materials and subprojects, power supply, electrical sheets, electronics connectors
  - `embedded computers`
  - `sensors`
  - `motors drivers`
  - `power supply`
  - `connectors`
  - `charging`
  - `power control`
  - `GSM/LTE/Bluetooth/LoRA connection`
  - `cameras`
  - `LIDAR`
- `software` - soft, diagrams, ROS implementation and cloud solutions
  - `Robot Operating System`
  - `protocols`
  - `data storage`
  - `autonomous algorithms`
  - `remote data acquisition`
  - `sensors plugins & procedures`
  - `bussines logic`
  - `cloud connections`
  - `failover connections`


See logs from [MEETINGS](MEETINGS.md)
