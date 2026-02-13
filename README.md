# Windborne Embedded Electrical Engineer Challenge Submission

## Project
For this project, I developed a PCB with 7 flickering LEDs to create a backlit board. My goal was to create the effect of a haunted house with flickering lights inside as a Halloween decoration.

## Design Feature
I routed ground between two different pathways (one for D4, and D5, another for D1, D2, and D3) by using D6 to split it across two different branches of the PCB. THis ensured that each LED's other terminal could connect to its respective resistor without a short. This was made more difficult by the numerous holes in the board (which form the "windows" in the haunted house). Initially, it was difficult to identify where the branched pathway should go because of the unequal distributions of space for LEDs (such that they could still be bent to light up the windows) across the board. In the end, I feel that the solution I found was elegant since the wiring was fairly evenly distributed throughout (improving debug-ability down the line).

## Files
- [pcb_schematic.pdf](https://github.com/ecwood/Windborne-Embedded-Electrical-Engineer-Submission/blob/main/pcb_schematic.pdf): This file shows the circuit schematic for my PCB.
- [pcb_routing.png](https://github.com/ecwood/Windborne-Embedded-Electrical-Engineer-Submission/blob/main/pcb_routing.png): This file shows the routing layout for my PCB, along with a description of one challenge that I solved.
- [halloween_pcb.jpeg](https://github.com/ecwood/Windborne-Embedded-Electrical-Engineer-Submission/blob/main/halloween_pcb.jpeg): This file is an image of my PCB built.
