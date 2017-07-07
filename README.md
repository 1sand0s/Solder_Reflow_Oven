<h1>Solder Reflow Oven Controller (2014)</h1>

<h3>About</h3>
I built this during my fifth semester course on control systems. It uses a AT90USB646 mcu to implement PID along with a AD595AQ temperature sensor.
This PCB was built at home using the PCB toner transfer method and hydrochloric acid/hydrogen peroxide as etchant.

<h3>Workflow</h3>

First up is the inventory . As for components , I have chosen ones which were readily available except for AT90USB646 which I wanted to experiment with for a long time .I have chosen AT90USB646 since the LUFA project by Dean Camera comes with examples of AT90USB1287 which is very similar to AT90USB646 for implementing the USB stack . I have included a transistor to drive the relay however for the relay i'm using this wasn't necessary since the AT90USB646 can source upto 40mA of current per I/O whereas the relay only needed 20mA but the relays you might use might be different hence the transistor.Okay , lets jump in then

![alt text](https://raw.githubusercontent.com/1sand0s/Solder_Reflow_Oven/master/IMG20170706134759.jpg)

For the toner transfer , after a few tries I experienced better results when after scrubbing the copper surface with steel wool I left the surface damp with surgical spirit and stuck the glossy paper to it and then proceeded with ironing it.

![alt text](https://raw.githubusercontent.com/1sand0s/Solder_Reflow_Oven/master/IMG20170707181938.jpg)

I used a HP Laserjet M1005 printer and Oddy Photo Glossy Paper. I was initially apprehensive about using this glossy paper since its meant for inkjet but I have used it several times since writing this and its never caused any damage to my printer and the paper peels right off after ironing leaving behind an excellent finish(note: I changed the crystal footprint to SMD since I realized I had a few left from a previous experiment)

![alt text](https://raw.githubusercontent.com/1sand0s/Solder_Reflow_Oven/master/IMG20170707183544.jpg)

