# DAY 1
 I
 I
M
 G
Day 1 LAB 1
 IMG
Day 1 Lab2
 IMG
Day 1 Lab 3
 IMG
Day 1 Lab 4 
https://github.com/efabless/OpenLane
 IMG
 IMG
Day1 Lab 5
No of Cells: 14876
dfxtp_2 = 1613
Flop ratio = 10.8429


# Day 2
Width & Height of the Core and Die
Utilization factor = Area of Netlist / Area of Core
Utilization factor less than 1 means there is more space left to add other required items
Aspect Ratio = Height of Core/Width of Core
Aspect ratio not equal to 1 means it is a rectangular chip, else it is square.
Pre placed cells
Big circuits with large number of gates (50000 gates etc) are divided in to blocks. Arrangement of IPs in chip is floor planning. These are placed first in the chip and called preplaced. Example - memory, clockgating etc. They can be re-used like functions.
Decoupling capacitor
Noise margin determines what range of voltage is treated as 1 or 0 (example - 4.5 to 5 V can be 1 and 0 to 0.5 v can be 0). Decoupling capacitor is placed all around the blocks and can act like a local power source very close to block, so reduces problem of voltage loss.

# Day 3
