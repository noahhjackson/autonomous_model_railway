# autonomous_model_railway
An autonomous model railway layout made in HO (1/87) scale. I am using JMRI as the base for the project. 

This project started when my Pa began construction of a new model train layout, and wanted to use Digital Command Control (DCC) (https://en.wikipedia.org/wiki/Digital_Command_Control) for the control method, rather than simple DC power. I constructed a power supply and built a DCC control system using the DCC++EX library for arduino and JMRI (https://www.jmri.org/) for a laptop. This involved some trial and error regarding the hardware, as components that I was told were compatible were not without non-trivial modifications or additional hardware. Before constructing the box, I created a model using Fusion 360 and then attempted to laser cut plyboard panels for the outside of the box. As we discovered, marine ply is not suitable for laser cutting, only laser engraving. However, this meant that the pattern was already etched onto the boards so we could cut them out with a band saw. 
![alt text](https://github.com/Rewind2B4/autonomous_model_railway/blob/main/Photos/65441996870__7E955F9D-B147-4E92-8015-57AE166576BB.JPEG)

![alt text](https://github.com/Rewind2B4/autonomous_model_railway/blob/main/Photos/65871434672__8B335532-7F05-4C36-9057-169314AE5A0B.JPEG)

When the box was complete, and the correct hardware was in place we were able to control the locomotives that we had using the DCC protocol. 

![alt text](https://github.com/Rewind2B4/autonomous_model_railway/blob/main/Photos/68878883848__64C89B25-A520-432F-B333-D68A2FE67732.JPEG)

![alt text](https://github.com/Rewind2B4/autonomous_model_railway/blob/main/Photos/IMG_6694.JPEG)

The next challenge was to add the functionality for a laptop to be able to control the turnouts on the panel. These are controlled using solenoids, which in turn are controlled by relays. After the construction of a relay board, we determined that the solenoids require 16V AC to function correctly, rather than the 12V DC that was being supplied. This involved adding another power supply, and a set of capacitors to store energy to move the solenoids when required. I also created a program that would allow for PC control, and control from a push button panel on the layout. This was a challenge because both systems need to be kept informed of what the settings of the other are, otherwise the two control methods would not be interoperable. 

![alt text](https://github.com/Rewind2B4/autonomous_model_railway/blob/main/Photos/IMG_0133.JPEG)

![alt text](https://github.com/Rewind2B4/autonomous_model_railway/blob/main/Photos/IMG_6966.JPEG)

So far this project has been 18 months work due to my studies and the complexities with the DCC and JMRI systems. 

Noah Jackson 23/02/2023
