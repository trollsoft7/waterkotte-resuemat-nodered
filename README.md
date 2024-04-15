<img width="1295" alt="image" src="https://github.com/trollsoft7/waterkotte-resuemat-nodered/assets/51830290/323fe60a-1a9b-4855-8921-15712c234661">


Hello,

I used FHEM on a Raspberry Pi to readout my Waterkotte Resümat CD4 via this
https://wiki.fhem.de/wiki/Waterkotte_heat_pump_with_Resümat_CD4

Having Home Assistant in use, I tried to integrate it via Node-Red:

Following palette needs to be installed:
node-red-contrib-home-assistant-websocket

node-red-contrib-buffer-parser

node-red-node-serialport

node-red-show-value


The heatpump is connected via USB-Serial-Port Converter

The flow reads out the Resümat every minute. Set Command are working for Heating onoff/warmwater onoff/temperature heating/temperature warmwater.

Use at your own risk!
