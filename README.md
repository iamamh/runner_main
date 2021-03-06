# Urban Facilitating & Maze Solving Robot

![](images/robo_assem.png)

__About the competition__: https://www.facebook.com/todaystalkmntv/videos/472765116948239<br>
<br>
This robot was developed for a Robotic Competition.
It has mainly two functionalities:</br>
- Solving Maze
- Dropping Cubes (on the way of solving the maze)<br><br>


>**Upon checking the codes, I would advise you to go through the file __runner_main.ino__ first as it's the main function and explore other ones after that eventually. A good command in C++ programming and familiarity with arduino microcontroller would help understanding these codes.**
<br>

The Robot Design was developed by [Htet R Kar](https://www.facebook.com/profile.php?id=100006272985879) and [Waiyar Aung](https://www.facebook.com/wai.aung.33).<br>
__Robot Model__ : [https://a360.co/35Twe6T](https://a360.co/35Twe6T)

### Robot Construction
Both acrylic plates and 3D printing parts were used for the robot body frame.<br>
[HAKSA Hardware Solutions](https://www.facebook.com/haksahardwaresolutions/), which provide quality 3D printing services in Myanmar, sponsored our team for this competition regarding 3D printing parts.


### Electronic Components List
- Arduino Mega - 1pc
- Ultrasonic Sensor HC-SR04 - 5pcs
- Color Sensor TCS3200 - 2pcs
- GM37-520 Gear Motor with encoder ( 320RPM ) - 2pcs
- VNH2SP30 30A Monster Motor Shield - 1pc
- LM2596 ADJ DC-DC Step-down Power Supply Module - 2pcs
- 2200mAh 3S 25C Lipo Pack - 1pc
- 4-lead Nema17 Stepper Motor 42 motor Nema 17 motor 42BYGH 1.7A motor for CNC XYZ - 1pc
- Stepper Motor Driver DRV8825 - 1pc

### Applied Engineering Knowledge
- Control Theory
- Embedded Programming
- Circuit Theory
- Digital Electronics
- Mobile Robot Design

### Game Details
Senior level competition of Myanmar Robotians Competition 2019 under the theme of __Urban Facilities Assistant__.<br>
<br>
This game is inspired from the idea of how robots can help to develop the basic requirements of a city. The game includes four basic requirements of a city: water, electricity, recycle system and greenspace.<br>
<br>
- The requirement will be represented by four different colors.
- Four teams will have to place their robots in the arena of competition.
- Arena will be divided into four parts, each representing a city.<br>
- Each robots have to take care of the necessity in its city.<br>
- The places with requirements is shown on the floor for the robots to detect.<br>
- Four blocks with different colors will be placed inside the factories.<br>
<br>
The robot will manoeuvre from the starting point to end point through the maze by detecting the colours on the floor and placing the blocks matching the color as it is carrying.<br>

### Furthure Development
The sensors utilized in this project (ultrasonic and color sensor) seem to be vulnerable to noises and exhibit unexpected and undesirable behaviour at certain times. __Sensor Data Filteration__ should be considered more meticulously on further development.

### Team Memebers
- [Aung Myo Htet](https://www.facebook.com/aungmyo.htet.9400)
- [Htet R Kar](https://www.facebook.com/profile.php?id=100006272985879)
- [Htoo Wai Yan Aung](https://www.facebook.com/profile.php?id=100008665359515)
- [Myat Min Thu](https://www.facebook.com/myat.minthu.315)
- [Waiyar Aung](https://www.facebook.com/wai.aung.33)

