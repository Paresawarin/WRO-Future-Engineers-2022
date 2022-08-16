# WRO-Future-Engineers-2022
All file for WRO Future Engineers competition #Team Boat Robot

**Explanation:**

For the WRO-future-engineers, there is a competition to show how teammates helped each other  

to solve a whole problem. The main problem belonging to Future-engineers is two composite problem sets. First, the game field standard uses the robot to walk through the field and have a wall along the road. The rule of this game is so easy that it just lets the robot walk through the whole field three-row at a time. Second the last problem these problems is as same as the first one but has an obstruction along the middle of the field. And the rule is as same as the one.

**Solution**

We have two main programs for encountering two-day solutions. which mesn is one for day-one and two for day-two.

**FIRST:**

The first solution is to let the robot in different places at six random around the whole field. The solution for our teams is to use two ultrasonic sensors to look at the wall and one color sensor to look at the line(Blue, Orange). First, we let the robot into the right position at random, and that it’s. The robot will run and use the sensor color to find the first line no matter the color (Blue, Orange). After finding the first line, the robot will run a little bit until finding the wall(ultrasonic in front of the robot) by the setting of the ultrasonic sensor at the same time, ultrasonic at beside of the robot will check a wall beside if not found wall yet which mean turn left but else turn right. After turning left or right, the robot will run in the same as the first for a long while to finish the whole field. 

**SECOND:**

The second solution is quite harder than the one. The method that we used to solve is rather the same as the one. But we added more sensors that a Camera used to classify the object (Green, Red) block. At first, the robot will leave in the same way as the one after the turn by using an ultrasonic sensor and color sensor that we mention. We used the camera to check the color of the block at the right spot(Circle). Even if the block is green, the robot should turn right to dodge an obstruction. In other words, if the block is red, the robot should turn left. Then, the robot will turn to the middle of the field to find the other block; no matter turn left or right, the robot must turn to the center. And the robot will loop as same as before.

Component:

- Ultrasonic Sensors
- Color Sensor
- Motors
- Board (EV3)
- Wheel
- LEGO
- Camera
