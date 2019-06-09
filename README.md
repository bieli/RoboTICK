# RoboTICK
RoboTICK - OpenSource &amp; OpenHardware robotic free platform (based on ROS)

Presentation from meetup about this project [Let's build a robot with ROS - Internet of Things, Hardware & Robotics meetup #1 Poznań](https://www.slideshare.net/bieli/lets-build-a-robot-with-ros-internet-of-things-hardware-robotics-meetup-1-pozna)

See logs from [MEETINGS](MEETINGS.md)


Project structure - divide by specific stuff
====
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

