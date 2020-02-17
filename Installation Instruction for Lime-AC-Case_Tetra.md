# Installation Instruction for Lime-AC-Case: Tetra

![](images/tetra/IMG_9320.JPG)
Here is what inside the box: fan, case, SMA to U.F.L cables, accessories pack.

![](images/tetra/IMG_1736.JPG)
Accessories.

## Preparation.
All you need is just Phillips PH0, PH2 screwdrivers, and Flat Round Tip Straight Tweezer.

## Step 1: Soldering the fan header pins.
**You can skip this step if you don't want the active cooling function.**

![](images/tetra/IMG_1483.JPG)
Remove the nylon support.

![](images/tetra/IMG_4636.JPG)
Soldering the fan header pin to the J14 connector on the board. 

![](images/tetra/IMG_3915.JPG)
**After soldered use a multi-meter to make sure the two pins are not short. Then combine the board with the bottom case to check if the pins are touching the bottom case or not. If touching the case, cut off the excess or resolder.**

Connect the fan and plug into the USB port to test the fan, if nothing wrong, the fan will spin and stop immediately.

**Notice: Fan will be turned on if the board will heat up to 55°C and FAN will be turned off if the board will cool down to 45°C.**

## Step 2: Mounting the PCB on the bottom case.

![](images/tetra/IMG_2528.JPG)
First, Make sure your board can be slid into the case, if not, just bend the USB port and made it level with the board.

![](images/tetra/IMG_5011.JPG)
![](images/tetra/IMG_9930.png)

![](images/tetra/IMG_6503.JPG)
Put the thermal paste on the memory chips and the nake crop on the bottom.

![](images/tetra/IMG_5914.JPG)
Slide the board back into the bottom case and secure it with the M2x3mm screws.

## Step 3: Install the clock cables and the LED indicator.

![](images/tetra/IMG_2300.JPG)
Put the LED indicator into the LED holes.

![](images/tetra/IMG_0118.JPG)

 - Mount the SMA-U.F.L cable to the CLK hole, and connect the U.F.L to the REF Clock connector show as **"In"**.
 - Mount the SMA-U.F.L cable to the REF hole, and connect the U.F.L to the REF Clock connector show as **"Out"**.

**Make sure no cables is on top of the USB chip and inductor.**

## Step 4: Install the RF cables(the hardest part).
In this part, a Flat Round Tip Straight Tweezer could be a lot of help.
![](images/tetra/IMG_2447.JPG)
It's not much difficult to install the TX cables, just make sure not to break the "GU" filter and no cables on top of the LMS7002 and Mosfet.

![](images/tetra/IMG_2475.JPG)
When you deal with the RX2_W connector, twine the cables so that it wouldn't on top of the LMS7002.

![](images/tetra/IMG_5674.JPG)
Then the RX2_L, just don't damage the "GU" filter.

![](images/tetra/IMG_9591.JPG)
RX2_H.

![](images/tetra/IMG_4076.JPG)
The bend the RX1_W and RX1_L cable into "S" shape, and deal with the U.F.L connectors as the above picture shows.

![](images/tetra/IMG_5500.JPG)
The last is RX1_H, similar to RX1_W and RX1_L.

## Step 5: Install Top case.

![](images/tetra/IMG_6407.JPG)
Paste the thermal paste on LMS7002, FPGA, USB Chip, Inductors and Mosfet.

![](images/tetra/IMG_3599.JPG)
Put the Fan cables through the top case and connect to the Fan header pins. The red cable should be connected to the positive pin.

![](images/tetra/IMG_0470.JPG)
Close the case slowly, make sure no cable is cliped. If the case can't be closed, open a seam and poke the clamped cables in with tweezers.

![](images/tetra/IMG_8714.JPG)
Secure the Fan with the M3x12mm screws.

![](images/tetra/IMG_3847.JPG)
Turn the case around, and screw all the M1.6*8mm screws.

###All Finish, have fun with the case.