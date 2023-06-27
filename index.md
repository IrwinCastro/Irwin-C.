# TableTop Robot 
The Tabletop Robotis is a useful tool kit that has aided me in the development of numerous talents. Furthermore, the Tabletop Robot interacts with its surroundings intelligently by employing motors, sensors, and computers. The tabletop robot is vital for getting started in engineering and progressing to the next level. In addition, the tabletop robot is very self explanatory detecting the edge of the table, then realizes it is going to tumble off and turns around avoiding the edge. This is a result of the following materials: Arduino, a motor driver, DC motors, IR sensors, and ultrasonic sensors are used in the device.  


| Irwin C. | John H. Francis Polytechnic Senior High School | Electrical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy
and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
In my second milestone, I built a basic piece of code that would aid me in the next step toward complete table top robot functioning. As a result, I used the sensor for line tracking, which allowed me to determine the sensor value and avoid the table's edge. Essentially, this sensor carries the pin number A0, which allows the sensor value to be appropriately analyzed to show whether the robot is on or off the table. When the sensor value detects that it is no longer on the table, my robot will stop, back up, turn, and continue onward. However, this is only a first step toward my eventual goal, therefore there will be several trials and errors along this process, such as coding. Coding is my weakest link, and I have a lot of them including having the correct sensor value to do my project correctly.

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy
and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
Thanks to the motor driver, Arduino, and Arduino library, my robot can move for my first milestone.

The inputs are connected to the motors and act as a bridge, allowing both motors to function at the same time. This affects the robot's speed and direction of movement. Additionally, I connected an Arduino to the battery pack and the motor driver to help with the power transfer required for the robot to work. Furthermore, the robot has a microprocessor that I can configure to go in any direction or at any speed. 

Finally, I downloaded the Arduino library to the motor driver to supply me with the code to move the motors, then I tried it and ran into some difficulties, such as overloading the arduino with numerous outputs, but once I found the problem, I rectified it right away. My plan for the future is to finish the rest of my project and hopfully and modifcations. 

[Untitled (Draft).pdf]

<iframe width="560" height="315" src="https://www.youtube.com/embed/4TMorQ3VmTU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing]( 14451_14450_sfe_motor_driver-dual_TB6612FNG_v11) 14451_14450_sfe_motor_driver-dual_TB6612FNG_v11.fzpz are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
