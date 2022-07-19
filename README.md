# RolandSH101
Collection of rework and notes on the Roland SH-101 Synth

A friend asked me to take look at his Roland SH-101 a couple years back.
I told him I could fix it.  He had it since high school (35+ years ago) 
and for some reason was not working.  I spent about a month or so 
trouble-shooting the unit and found the root cause was the T1 transformer.

The main root cause was a bad power supply transformer.

I re-capped the board anyway, and replaced nearly every passive and 
transistor.  All of the ICs except MCU and Roland OEM parts were replaced
also.  I left the original LEDs.

I rebuilt the bender-mechanics, new hardware and also replaced some worn
out pots with new ones.

It was re-calibrated per specification (Lissajous figures, etc..).

I rebuilt a solid state DC-DC converter + LDO based power supply.

I'll post schematics of that soon.

The MAIN THING to remember is that modern day wall-wart power supplies will FRY
your SH-101.  DO NOT USE THEM.  DO NOT PLUG IN ANY OLD WALL WART INTO SH-101!!

On the SH-101, the ring is positive (+) and the pin is negative (-).  If you
don't believe me, read the schematic.

On modern day wall-wart the ring is negative (-) and the pin is positive (+).

If you think your unit is busted, there's a good chance it is not and can
be fixed.  Only an expert is going to be able to tell.  Choose wisely.

I can (and will) list a few things that I look for when troubleshooting.

## Bill of Material

[Bill of Material Lists](./bom/BOM.md)

