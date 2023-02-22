# autonomous_model_railway
An autonomous model railway layout made in HO (1/87) scale. I am using JMRI as the base for the project. 

This project started when my Pa began construction of a new model train layout, and wanted to use Digital Command Control (DCC) (https://en.wikipedia.org/wiki/Digital_Command_Control) for the control method, rather than simple DC power. I constructed a power supply and built a DCC control system using the DCC++EX library for arduino and JMRI (https://www.jmri.org/) for a laptop. This involved some trial and error regarding the hardware, as components that I was told were compatible were not without non-trivial modifications or additional hardware. Before constructing the box, I created a model using Fusion 360 and then attempted to laser cut plyboard panels for the outside of the box. As we discovered, marine ply is not suitable for laser cutting, only laser engraving. However, this meant that the pattern was already etched onto the boards so we could cut them out with a band saw. 

When the box was complete, and the correct hardware was in place we were able to control the locomotives that we had using the DCC protocol. 

The next challenge was to add the functionality for a laptop to be able to control the turnouts on the panel. These are controlled using solenoids, which in turn are controlled by relays. After the construction of a relay board, we determined that the solenoids require 16V AC to function correctly, rather than the 12V DC that was being supplied. This involved adding another power supply, and a set of capacitors to store energy to move the solenoids when required. I also created a program that would allow for PC control, and control from a push button panel on the layout. This was a challenge because both systems need to be kept informed of what the settings of the other are, otherwise the two control methods would not be interoperable. 

So far this project has been 18 months work due to my studies and the complexities with the DCC and JMRI systems. 

Noah Jackson 23/02/2023
