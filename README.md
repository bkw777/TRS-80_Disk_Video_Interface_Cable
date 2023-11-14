# 3-part Cable for TRS-80 Disk/Video Interface

![](kit.jpg)

Pics: https://photos.app.goo.gl/Jy1hXhc3aSbkcaFr6  
Parts: [DigiKey](https://www.digikey.com/short/22hnb0rh)  
Optional soldering helper PCB: https://oshpark.com/shared_projects/EoeBHp2k  
Ribbon for connector-pull: https://www.target.com/p/orange-birthday-ribbon-spritz-8482/-/A-86900836

This cable kit supports all 3 computer models that the Disk/Video Interface supports: TRS-80 Model 100, TANDY Models 102 and 200

Aside from the Model 100 bus connector, all connections are polarity protected and can't be accidentally connected any other way except the right way.

## Usage
On the D/V-I, The connector is on the underside of the box, and the plug must be pressed firmly enough to cause the two latches to snap closed.

### TRS-80 Model 100  
Use all 3 parts connected together.
Plug the Model 100 adapter cable into the bus connector socket with the cable going directly towards the rear of the computer without having to fold back over the top of the bus connector.
The red stripe should be towards the battery compartment.

### TANDY Model 102 or 200
Use only the main cable and twist adapter connected together.  
The twist adapter plugs directly into the back of the computer.

## Construction

### Part 1 - Main Cable  
Take one of the 2 pre-made cables and put it to the side. This is the main cable and will be used unmodified later.

### Part 2 - Twist Adapter  
Solder the 2 narrow 40-pin pin headers to each other, back to back, with the polarity notches on opposite sides from each other. One connector notch-up, the other connector notch-down.  

This will make pin #1 on one connector go to pin #2 on the opposite connector. This is correct.  

Optionally use the soldering helper pcb for this if you want. It's not needed, but it is easier.  

Optionally cover the pins with hot-glue and fill the gab between the connectors.  

It's called the twist adapter because it has the same effect as seperating all 40 wires into 20 pairs, and then giving each pair 1/2 twist.

### Part 3 - Model 100 Adapter
Cut the remaining pre-made cable in half, so that each half is about 8 to 9 inches long.

Place the DIP-40 connector on your work surface with the pins down and with the two rows oriented vertically.  
Mark the top-left corner to indicate pin 1.  
The connector is symmetrical and has no pin-1 mark itself, you just pick either end and mark it.  

Place both cut cables flat on the table to the right of the DIP-40 connector with the cut ends to the left and the connectors to the right, and the red stripe up.  
If only one of the connectors has the polarity bump facing down, use that cable and discard the other, otherwise pick either one.  

Insert the cut end of the cable into the DIP-40 connector, maintaining the orientations from above: The DIP-40 is pins-down with the pin-1 mark to the top-left, The DIP-40/cut end is left and the female IDC is to the right, the red stripe is up.

Maintain this assembly without seperating the parts or losing the current orientation of the parts while you crimp the DIP-40 in a hobby vice.

You want the final result to be for the cable to go directly from the DIP-40 system bus connector straight back to the rear of the Model 100, with the polarity bump pointing up, and the red stripe on the side facing the reset button. (but don't plug it in all the way yet, we still need to attach an extraction loop to make it easy to unplug without bending the pins)

Finally take an 8 inch length of 3/8" fabric ribbon and hot-glue one end of the ribbon to the bottom of the DIP-40 connector in between the pins. Cover the whole length of the connector with ribbon and press it flat before it cools.  
Loop the ribbon over the top and glue the other end to the bottom to form a closed loop, again overlapping the full length of the connector with ribbon.  

In order to protect the pins from bending when extracting, it's important that all of these things are true:  
1 - The ribbon forms a closed loop.  
2 - The ribbon is fixed to the connector so that the loop cannot slide relative to the connector.  
3 - The ribbon is not elastic.  
4 - Your fingers are not slippery with soap water or something when pulling on the loop.

With that, even when you pull the loop off-center, the ribbon forces the connector to stay parallel to the socket and the pins don't get bent when the connector starts to break free.

When installed, the female IDC connector will just clear the rear of the model 100 and provide essentially the same connector, orientation, and pinout as a 102 or 200.

