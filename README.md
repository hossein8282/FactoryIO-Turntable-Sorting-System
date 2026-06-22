##  Project Assignment

**Objective:** Design and implement a sorting and routing process for boxes based on their height in the Factory I/O environment using PLC programming.

**System Description:** In the schematic of this system, three types of boxes—**Box (S)**, **Box (L)**, and **Palletizing Box**—are placed on the infeed conveyor. Upon entry, the boxes move onto a Turntable where their height is detected by a height sensor.

**Main Control Tasks:**
1. The sorting process must initiate when the **Start** button is pressed.
2. After detecting the height of a box, the Turntable must rotate in the appropriate direction to route the box to its designated exit path (the assignment of specific exit paths to box types is customizable).
3. A sensor located at the beginning of each exit path counts the passing boxes. The total count for each box type must be shown on its dedicated **Digital Display**.
4. Pressing the **Reset** button must reset all counters to zero.

**Hardware Specifications:**
* **Inputs:** Start button, Stop button, Height sensor, Exit path sensors, and Reset button.
* **Outputs:** Conveyor motors and actuators, Turntable rotation mechanisms, and Digital Counter Displays.
