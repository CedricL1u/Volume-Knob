title: "Volume Knob"
author: "Cedric"
description: "A volume knob with a LCD screen on top powered by a RP2040 and custom PCB"
created_at: "2024-06-10"
**Total time spent: 15h**


# June 10th: Got the schematic layed out!
Took a while to lay out the schematic as it was my first time designing a PCB. It also took me a while to find a suitable round LCD as most of them weren't compatible with the rp2040 or either had a flex pcb which seems hard to solder. When I began to draw out my schematic, I realized that there was no symbol for the screen so I ended up having to learn how to create my own custom symbol. I chose the EC11E encoder because it had satisfying clicks when you rotate it and also a integrated button which I plan to use for pause controls. It also took quite a bit of time figuring out what pin to connect to what since I've never designed a pcb before. 

![image](https://github.com/user-attachments/assets/606b7c35-3b3f-4865-a3cf-a6582a6a0e58)

**Total time spent: 6h**

# June 11th: Got my PCB layed out!
I was a bit confused with how to center things as I'm used to CAD software where you can easily constrain and dimension things. I eventually found the move to exact position tool which was really helpful in creating precise placements for everything especially mounting holes in my pcb. 

![image](https://github.com/user-attachments/assets/a26349f6-f7d0-49e2-9705-bcf6d7732bdc)

**Total time spent: 4h**

# June 12th: Started designing my case
As I was designing the case, I realized that my initial desing of having my rotary encoder face upwards towards the screen wouldn't work. I pivoted by changing it so that the rotary encoder is upside down that way, it still retains the click and I dont have to redo my pcb. Also since the screen wasn't perfectly round, I extended the screen cover a bit more to make it seem round when it really wasn't.
![image](https://github.com/user-attachments/assets/fd327a0c-0860-4a7c-a724-841a0a5685b6)

**Total time spent: 5h**

# June 25th: Programming the raspberry pi
I decided to use circuitpython to program the screen because it was apparently the most beginner friendly language. I've never coded a microcontroller before so I just decided to start with a simple program the flashes the LED. This took ages to get working even though I just copy pasted code from the Seed Studio Xiao rp2040 documentation. Later I found out that the code was actually working, just blinking another LED that was really small and hard to see. The LED I wanted it to blink was called NeoPixel which I eventually got working.

https://github.com/user-attachments/assets/7845eadc-a8b4-4a9f-9cb8-2a3589337535

# June 26th: Trying to get the screen working
After hours of trying to get the screen working with circuitpython and looking at open source code I couldn't get it working. I decided to just switch to Arduino IDE and learn C because there were more resources for it. After downloading the Arduino IDE I got the LED flashing within seconds, there was so much documentation on Arduino and it felt way easier.








