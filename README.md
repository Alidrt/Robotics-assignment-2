Robotics assignment 2 read me 

Resources: 

Processing, https://processing.org/. To have a deeper look in how to use processing to create the GUI. 

Zumo32U4 example code such as the line follower, proximity and line sensors and motor code. 

Arduino website, https://www.arduino.cc/. To enhance my understanding of the code and using the Arduino IDE. 

Zumo website, https://www.pololu.com/product/2509. To understand how the Zumo works such as where the sensors are located. 

 

Mode 1 

For mode 1 first I looked at my previous assignment work and looked at the motors example to remind myself of how the motors worked once I got the motors to work, I had a look at the robot arm sketch and used similar case statements to move the motors depending on the character pressed and to use the serial to take in commands such as appropriate key board presses for example l to turn left and send messages to the user such as “robot in front ATTACK!!!”. I had a look at the Arduino examples from week 1 and week 2 to remind me how to write to the serial monitor. Also had a look at the line sensor examples and the buzzer example so that it would buzz if it detected the other robot. 

 

Mode 2 

 

For Mode 2 I built upon mode 1 and my previous mode 2 code from assignment 1 and incorporated proximity sensors so that it could detect an object and implemented different if statements for different scenarios such as when on the edge of the arena switch to manual mode. Originally, I started off by having the same threshold value for detecting being on an edge or detecting an edge on the side but later changed this so that the code for detecting being on the edge is greater. 

I further optimised and refined my code from the first draft where from only having a manual mode and the loop to also incorportaing an autonomous function as seen in the final version of mode 2.  

Switches to manuaul mode when detecting that it is on an edge and once the user can press t to move away from the edge or fully control what the Zumo does. 

Once the manual mode is complete it prints a statement letting the user know that it is switching back to automatic mode. 

 

Mode 3 

 

Built upon mode 2 but making it fully automatic by reversing away and then turning left when encountering an edge. Implemented if statements which detects that its on the edge and reverses and moves to the left. 

In the final iteration condensed and further optimised and refined the code as I realised that I did not need so many if statements and opted for simpler code which greatly reducing the code written and required, optimising the code. 

 

GUI 

Implemented keyboard presses so now we can control the Zumo without a serial monitor or by pressing buttons. 

 

To start 

Upload the appropriate mode which you want to test to the Zumo, then run the Gui after closing the Arduino code. 

For mode 1 you just need to either press the buttons or the appropriate keyboard presses. 

For mode 2 it is like mode 1 but also has an autonomous mode. 

Mode 3 the Zumo should automatically start without user interaction 

1) Clone the repository 

2) Open folder named Final. 

3) Open the mode you want to test, example – Mode 1 then upload it to the Zumo via USB cable. 

4) Close the Arduino IDE. 

5) Open the Processing files and run it. 

 

Recordings 

Recording of screen: 

https://youtu.be/Akcr6E4ZxVE 

Recording of Zumo: 

https://youtu.be/Ek36eSgUMl0 

Time stamps in the description of each video. 
