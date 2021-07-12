# Robot Challenges

Regardless of the robot you choose, Your challenges will be the same.

1) Choose your robot
2) Get the software started
3) Begin the challenges
4) For each level you achieve, show Mr. Roth-Ritchie the accomplishment...

## The Levels

## Level one

### Make your robot move

**Aliens are attacking planet Alpha One where your robot safely resides. Your first task is to save your robot from the initial attack. As long as you can move your robot at least twice its size on the playing field, you will successfully evade their attack...
...For now.**

Use the chosen robot documentation to figure out how to load the software, connect to the robot, and make it move.
Here are links to the documentation of the various robots...

**FRC:** These Robots use VS Code

- Full-sized
- Romi

**Non FRC:** These robots use different programs to control them.

- Maqueen: Makecode
- Zumo: Arduino
- Finch: Makecode, or VScode

## Level Two

### Dead Reckoning

**Whew, you made it. Your robot has just been teleported to the game field. You will need to mark up the field as we go forward.**

**Speaking of going forward, you see the aliens right behind your bot. You need to go through the next portal before they get to you. However, there is a catch. You can see the entrance to a labyrinth dead ahead. If you hit the wall in front of you, you will trigger a not so well hidden trap.**

Make your field resemble the diagram below.

Drive your robot 3 lengths forward, but make sure it stops before it hits the wall in front of it. Use a timer to control when the robot stops.

<details>
  <summary><b>Hint</b> (click the triangle to reveal more details about this hint):  You may want to consider creating an algorithm to accomplish this task. </summary>
 In programming, an algorithm is a specific procedure for  solving a problem. You can find more info at <a href= "https://www.programiz.com/dsa/algorithm"> here</a> or in lesson 6 of the Maqueen resources. Often times, adroit programmers use flow charts to map out their algorithms. using arrows to visualize all possible outcomes. 

<details> 
<summary> <b>Here is an example that could be used for this task.</b> </summary> 

 ![Dead Reckoning flowchart](/images/deadReckoning.png)
 </details>

 You may use <a href = "https://lucidchart.com"> LucidCharts </a> to create your own flowcharts. There is an <a href = "https://www.gliffy.com/blog/guide-to-flowchart-symbols"> entire vocabulary of flowchart icons</a>, but you could use whichever for now,as long as you know what the icons you choose represent as you intend them (and will be able to do so later).
  
</details>

## Level 3

### Encoders

**You made once again, but the Aliens are still right on your tail.** Using a joystick, or physically picking up your robot (depending on your robot), turn it 90 degrees. Repeat the above exercise to drive to the end of the wall using encoder ticks.

Hint:
In order to accomplish this, find out how many ticks it takes to drive a specific distance and then how much distance is involved in getting to the end of the wall. You may ask Mr. R^2 for help determining the distance per tick. Or, you may use the formula below.

distance per pulse = (pi*wheelDiameter)/encoderCountsPerRevolution

## Level 4

### Turn to an angle

**You are getting to the escape, but you need to navigate through the maze to get to the end of the room.** Use either the gyro or an encoder to turn 90 degrees. then, drive the remaining leg to escape the room.

## Level 5

### Line Sensor

**As you leave the room, you notice your robot is warped onto the Alien's spaceship. Their walls are invisible, yet, for some reason, they provided a marking on the floor to help you navigate to an escape.** Using electrical tape, mark the game field with the pattern you see below. Use a line sensor to help you get to the escape hatch.

<details> 
<summary> <b>Hint</b> </summary> 
 - You may use the Maqueen line sensor tutorial to help you build your algorithm. <br>
 - If you are using an FRC robot, you can use our Vex Line Sensors to navigate your way out.
</details>

## Level 6

### Rangefinder

Just when escape was within your grasp, your robot is catapulted into a room infested with Aliens.

Put aliens in the spots marked with an X. Use a rangefinder to help you navigate around them.

<details> 
<summary> <b>Hint</b> </summary> 
 - You may use the Maqueen ultrasonic tutorial to help you build your algorithm. <br>
 - If you are using an FRC robot, you can use our Maxbotics Analog distance Sensors to navigate your way out.
</details>

  
---
Congratulations: You have escaped


