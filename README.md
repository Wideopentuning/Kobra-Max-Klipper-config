So my Kobra Max wasn't awesome out of the box.  To be fair, I snagged it off of Ebay as an open box return from Anycubic for $250 shipped in early 2023 so I was going to be 
happy as long as all the parts were in the box.  When it arrived, it was essentially brand new with a slight tweak in one rear corner of the bed where it may have been dropped
before packing because otherwise it looked unused.   I set it up and ran it stock for about 3 days before pulling the Trigorila board out and performing the R65 to R66 resistor 
move so I could run Klipper with control of all the steppers.   That was fun for a week but the super taco shaped bed, bowden extruder and very inconstant strain gauge probe
had me frusterated.  I tore it down to the frame and then fitted a Honeybadger MGN12 rail to the X gantry but then got busy with other.....printers.   I started gathering parts
slowly deciding on a plan to try and "fix" this thing.   I decided on a BTT SKR Pico main board but using it as a CAN bridge to a BTT SB2209 toolhead board.  This printer screams
for a .8 nozzle and I had been impressed with how much flow I get from an Ali Express Bambu clone hotend with CHT style nozzle on my Voron 2.4.  At the much lower speeds this machine 
runs, it does great flow wise up to around 29mm/s³ and they heat to PLA temps in around 12 seconds.  The Stealthburner with 5015 fan isn't ideal for cooling PLA this fast so some form
of auxiliary fan similar to what Elegoo is using on their Neptune Pro series will happen soon.   Another easy near plug and play upgrade is the Y motor from the Kobra 2 Max. It is a 42-60 
as opposed to a 42-48.  To eliminate layer shifts in Y, the amperage needs to be bumped pretty heavily on the smaller Y motor.  I run accels at 3600.

I will update this more as the project progresses and add links to STLS and other helpful repositories 
