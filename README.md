<img width="1768" alt="image" src="https://github.com/trollsoft7/waterkotte-resuemat-nodered/assets/51830290/2712a159-7bb5-41a2-ae21-9e87d5e35b1a">

Hello,

I used FHEM on a Raspberry Pi to readout my Waterkotte Resümat CD4 via this
https://wiki.fhem.de/wiki/Waterkotte_heat_pump_with_Resümat_CD4

Having Home Assistant in use, I tried to integrate it via Node-Red:



The heatpump is connected via USB-Serial-Port Converter

The flow reads out the Resümat every minute. Set Command are working for Heating onoff/warmwater onoff/temperature heating/temperature warmwater.

Use at your own risk!
