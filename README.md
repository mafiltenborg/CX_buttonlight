# What's this?
Incandescent bulbs are used in the most bizarre places in older cars - and they're often hard to replace when they burn out.
This repo holds a tiny pcb with LEDs, designed to replace one of these specialty bulb-PITAs - once and for all!

# Which & where
The particular bulb being replicated/upgraded is located inside the toggle-contacts for eg electric windows or demister switch in the Citroen CX S2 (late model '86 onwards). Replacing requires disassembly and fairly good motorskills on your part. The design uses 0805 SMDs, making it, well, possible as least. I'm too old for 0402...

# How
To replace, get hold of a number of the little PCBs (17 x 5,5mm) and solder them up. 
Next, for every contact you want to upgrade, do
* Open up your contact and extract the yellow opaque plastic thingamabob.
* Remove the burnt-out bulb and slide in a LED-replacement circuit. Re-wire the yellow thingamabob.
* Plonk in the thingamabob and do a test run. If it doesn't light up, try turning it 180 degrees - polarity matters...

Further tweaks may include modding the value of R2 to get a sensible light output. LEDs are in fact quite bright and 'much' may not be the right choice for you. The circuit is not designed for power hungry LEDs as it uses a linear regulator. 

LEDs differ. To figure out the value of R2, use the formula

Vout = 1.25 * (1 + R2/R1)

To calculate.

Don't modify R1, as this may create instability.