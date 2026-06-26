# Gerbers for the Miniprobe

Use the PCB fab of your choice. I prefer JLCPCB since I'm in the states and they have the ability for me to prepay any tariffs to avoid "privilege fees" tacked on by shipping companies for the privilege of them collecting the tariffs from me.

If you use white or blue LEDs adjust the resistors used to fit within their operating voltage and current limits AND within the current limits of the 74LS06.

The 74LS06 can sink up to 40ma of current per gate with a maximum of 100ma across all six gates. Try to keep the LED currents to under 16ma each to stay under that 100ma limit if all 6 are active simultaneously.
