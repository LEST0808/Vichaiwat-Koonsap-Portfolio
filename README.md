# <img src="https://iam-weijie.github.io/wave/hand-emoji.svg" alt="Animated Emoji" width="50" height="50"> Hi, My name is Vichaiwat Koonsap.

# About me
## Profile:
I am a Computer Engineering and Digital Technology (CEDT) student at Chulalongkorn University with experience in robotics since 2019. Over the years, I have developed autonomous robotic systems involving embedded programming, computer vision, sensor integration, control systems, and mechanical design.

I have competed in both national and international robotics competitions, including achieving 7th place internationally at WRO Future Engineers 2023 in Panama, First Runner-Up at RoboCup Singapore 2025, and First Place at TPA Robo Rescue with micro-ROS 2025.

Beyond competing, I have led the Yothinburana Robot Club as President, mentored junior members, and helped organize robotics activities and training programs.

I am currently expanding my knowledge beyond robotics into software development, machine learning, and computer vision, with the goal of developing intelligent systems that combine software, hardware, and AI.

## Contact Information
- Tel: (+66)094-817-8817
- Line ID: gain20052551
- Gmail: gain2551@gmail.com

## Skills:
### Software:
<img src="https://github.com/LEST0808/Vichaiwat-Koonsap-Portfolio/blob/main/resources/Arduino.png" width="75" height="75"> <img src="https://github.com/LEST0808/Vichaiwat-Koonsap-Portfolio/blob/main/resources/cplusplus.png" width="75" height="75"> <img src="https://github.com/LEST0808/Vichaiwat-Koonsap-Portfolio/blob/main/resources/python.png" width="75" height="75"> 

### Hardware:
<img src="https://github.com/LEST0808/Vichaiwat-Koonsap-Portfolio/blob/main/resources/fusion.png" width="75" height="75">

### Robotics Control System:
- Autonomous Navigation
- PID Control
- Sensor Integration
- Sensor Fusion
- ROS 2 / micro-ROS
- LiDAR
- AMCL
- Omnidirectional Robot Control
- Embedded Systems

### Computer Vision
- Object Detection
- Object Tracking
- Image Processing
- Camera-based Robot Control
- YOLO
- MediaPipe
- OpenCV

### My Robot Designs


### Personal Skill:
- Team Leadership
- Technical Mentoring
- Project Management
- Cross-functional Collaboration

## Education:
- ### Primary School: Chonprathan Wittaya School (English Program) (Y1-Y6)
- ### High School: Yothinburana School (Regular Program) (Y7-Y12)
- ### College: Computer Engineering and Digital Technology(CEDT), Chulalongkorn University (Currently First Year)

# Competitions
## **International Competition:**
- ### <img src="https://github.com/LEST0808/Vichaiwat-Koonsap-Portfolio/blob/main/resources/thaiflag.png" width="20" height="20"> WRO Future Engineers International, Panama 2023: 7th place out of 60 countries. <img src="https://github.com/LEST0808/Vichaiwat-Koonsap-Portfolio/blob/main/resources/thaiflag.png" width="20" height="20">
This competition was my first experience competing at an international level. It was held at the Panama Convention Center and featured teams from more than 40 countries, including the United States, Germany, Japan, and Canada. I achieved 7th place, allowing Thailand to be announced during the award ceremony.
I used a POP-32 microcontroller as the main control unit, programmed using the Arduino IDE. For the mission, a camera and an ultrasonic sensor were used to help the robot navigate through the obstacle without hitting them. And for the robot to know where to turn, that is where the light sensors came in. There are two light sensors with separate colors, one is red and the other is blue. Red detect the blue line, causing the robot to turn counter-clockwise while blue does the opposite. In addition to system development, I was responsible for preparing technical documentation required for the competition.

- ### 🥈RoboCup Singapore Soccer Open 2025: First Runner-Up🥈
I competed in the RoboCup Junior Robot Soccer category, using an ESP32 as the main controller for its Wi-Fi capabilities. The robot was mechanically designed in Fusion 360 and programmed using the Arduino IDE. For vision and control, the robot tracked an orange ball using PID control and a conical mirror to achieve omnidirectional awareness. Two cameras were used: OpenMV for the conical mirror system and Pixy2 for front-facing ball tracking. The robot were able to move to any direction without turning with the help of an omni-directional wheel(Wheels with small wheel on the outside). The wheel were place separately with 90 degrees apart. With basic physics, we can calculate the power of each motor to make the robot move to each direction.
This was my second international competition, held in Singapore. At the start of the competition, our performance was below expectations. However, after iterative software adjustments, the robot showed significant improvement, and our team ultimately achieved second place.

## **National Competition:**
- ### 🥇TPA Robo Rescue With Micro-ROS 2025: First Place🥇
Robo-Rescue with microROS is an autonomous robotics competition focused on obstacle avoidance and survivor search.  The competition uses microROS, a lightweight subset of ROS 2 (Robot Operating System 2) that has been adapted to run on microcontroller boards such as the ESP-32. This is my proudest achievement because the competition underwent significant changes compared to the previous year. One of the major changes was the introduction of microROS instead of a conventional standalone C++ system, which greatly increased the technical difficulty. Before being allowed to compete, teams were required to pass a selection process. With limited time to prepare, I independently researched the microROS system and its architecture in order to understand its communication framework and successfully prepare for the test.

After qualifying, my team began developing the robot for the competition. During this phase, we identified a critical issue in which inconsistent LiDAR data caused inaccurate localization and incorrect navigation paths. I resolved this problem by tuning the parameters of the Adaptive Monte Carlo Localization (AMCL) algorithm to improve localization accuracy and prevent map instability. After applying these adjustments, the robot was able to navigate reliably and complete all tasks successfully. As a result, our team achieved a perfect score, becoming the only team to obtain full scores in three consecutive rounds.

- ### 🥇WRO Future Engineers Thailand 2023: First Place🥇
WRO Future Engineers is an autonomous robotics competition that integrates programming and mechanical design, making it well suited for aspiring engineers. The objective is to navigate a car-like robot through a course by avoiding obstacles and completing a parallel parking task.

For this competition, I built a robot using an Arduino Uno with a motor driver and sensor shield. I implemented a vision-based obstacle detection system using a camera, combined with ultrasonic sensors for distance measurement. A PID control algorithm was used to regulate the steering servo and maintain stable trajectory control. With this system, the robot successfully completed all tasks and achieved first place, and granting me the chance to compete internationally at WRO Panama.
Through this competition, I strengthened my understanding of computer vision and sensor fusion.

- ### WRG Soccer Robot 1x1: 4th place 
This soccer robot uses 3 motors, each placed at 120 degrees apart. We developed a function which help us control those movement better, giving us the ability to move to any position we want without turning with the help of omni-directional wheel. I use a camera to track the moving orange ball on the field, using a function which tracks how far the ball is from the robot, giving us a better approach toward the ball. I designed the robot with a place to hide an additional weight inside, making the robot able to push the opponent out of the way.

- ### WRO Future Engineers Thailand 2024: 4th Place
This is my second time competing in this competition. Although with our experiences, we should've gotten a better result. But unfortunately, our microcontroller broke during the second competition day and we have no replacement, dropping us to fourth place.

- ### PIM Robotics Playground Line tracing Open: Participate
This was one of the simpler competitions, as it focused primarily on line tracing. We use a simple PID algorithm with 8 sensors to help robot stays on track. I also designed the robot frame using Fusion 360, it helps the robot to stick closer to the ground, avoiding drifting. Although the robot itself is easy to make, the competition is hard since it was time based. We performed our best but the other uses faster motor, which we cannot keep up. I learned the information about the motor and bought it for the next 46 ICT line tracing competition.

- ### 🥇46 ICT Fast Line Tracing Competition: Gold Medal🥇
This is a fast line-tracing robot competition for grade 10 to 12. I used PID formula with 8 sensors to follow the line combining with 3D printed frame. Combining those with the faster motor we got from the last PIM competition, we were able to achieved a gold medal.

- ### 🥇Silipa 71 Intermediate Robotics Grade 10-12: Gold Medal🥇
This competition focuses on utilizing light sensors. There are two rounds of competition: normal and maze. The normal we were given 1 hours to prepare for the track that every competitors know how it looks, "I developed a modular function that allowed me to rapidly implement the control logic for different sections of the track.. The maze is a little more complicated since the robot needs to run on it's own without knowing what the tracks looks like. I wrote a program that makes the robot walks block by block, and after each block, the robot turns right to check whether there are black line or not. If there is, it saves the current position using simple array and walks forward until it can't find another way. Then it will comeback to the saved position and start again on other direction. With this algorithm, we were given a gold medal.

- ### 🥈LEGO Robot Battle: 1st Runner-Up🥈
This competition relies heavily on hardware rather than software. The hard part is designing and building the robot. Since it was made using a Lego Technic parts, there are a lot of restriction to put each part together. And after designing the core movement system, we need to look into the weapons. I chose a Lego separator tool. By flipping it upside down and place at the correct angle, It has the ability to scrape the floor and ram the opponent's robot. And the software uses a simple Bluetooth function. There is a remote and robot brain. The remote sends the data via Bluetooth to the brain with if-else logic. For example, if the left-back touch sensor is activated, the left motor would move forward.

# Activities
## Educational Activities
- ### NECTEC Smart Summer Internship
I successfully qualified for a research internship at the National Electronics and Computer Technology Center (NECTEC) from March 24 to April 30, 2025. I worked in the Image Processing and Understanding(IPU) Department under the Artificial Intelligence Research Group(AINRG). During those times, I worked on 3 projects; 
-Hand Gesture Detection
-Vehicle Tracking
-Real Face and Photo Classification

Vehicle Tracking: Developed a YOLO-based vehicle detection and tracking system to identify vehicles and extract attributes such as license plate information and color.

Hand Gesture Detection: Used MediaPipe hand landmarks with OpenCV to detect and process hand gestures from camera input.

- ### Yothinburana Robot Club President
I was appointed President of the YB Robot Club, where I was responsible for mentoring junior members and preparing teams for various competitions. I shared technical knowledge and competition experience to help members improve their performance and problem-solving skills.
I was also responsible for selecting new members through a screening process that was later voted on by senior members of the club. Through leading the club, I developed strong leadership, communication, and team management skills, as well as the ability to effectively prepare teams for competitive environments.

- ### Harbin Engineering University AI Training Camp
From March 27 to April 24, 2024, I participated in a one-month summer study abroad program in Artificial Intelligence at Harbin Engineering University. During the program, I studied fundamental concepts in AI and basic logical reasoning, which strengthened my understanding of the field. I also had the opportunity to visit research laboratories and observe academic research environments. Through this experience, I gained valuable insights into artificial intelligence, university life, and living in a dormitory.

- ### TPA 2024 Test
Completing an online qualification examination to earn a position in TPA RoboRescue 2024.

- ### YB Robot Starter Camp
Each summer, the YB Robot Club organizes a robotics camp for students interested in robotics. As a senior member and club president, I was responsible for planning, managing, and overseeing camp activities. The program covered fundamental robotics concepts, including logical thinking, mechanical assembly, and programming. Through leading this camp, I further developed my sense of responsibility, leadership, and management skills.

- ### YB Robot Open House
Hosted a booth to promote the YB Robot Club to students attending the Yothinburana Open House and are interested in Robotics.

- ### Thailand’s National Outstanding Youth Award
Presented to youths who represents Thailand in international events. 

- ### Honorary Award for Exemplary Yothinburana Student
Presented to students who enhanced the school’s reputation through their achievements.
