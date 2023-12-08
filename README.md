𝝺-𝝤𝝘𝝬

Lambda-OGX

A single board solution to combine several Original XBOX modifications. 
OpenXenium/OGX360/BlueRetro/spi2par2019/Wireless Bridge/
(Plus additional support circuitry)



Some Parts so far:

4 AT mega 32U4 are used for OGX360

1 AT mega 32U4 is used for spi2par2019

1 ESP32 is used for BlueRetro and communication with OGX360

1 ESP32 is used for linking all together and possible Wi-Fi?

1 Wi-Fi to Ethernet adapter (Possible use of ESP32?)

1 FPGA is used for OpenXenium



1 PCB to add all of these together. 

RGB that can tie into the spi lines of the OpenXenium? 
WLED? 

Use as many existing internal connections as is possible. 


Why?

Simple, I want to make an Ultra Slim OG-XBOX. To do this i will be removing the DVD drive,
adding in a 2.5" storage solution (ide to sata adapter). Removing the front controller ports,
with the combination of BlueRetro and OGX360 I will be able to use a DS4 pad or a Boone pad etc. 
As such I will have zero need for plug-in controllers.

In making the Ultra Slim I shall be trying to also provide a custom power supply with regulators etc. 
All Capacitors to be replaced with Solid state caps. But these won't be part of Lambda-OGX, just a cap replace. 

If it is possible to tie each mod together with a custom pre environment I shall try. 
I know that a few solutions already exist provide a pre environment for settings / mod configuration. 

Any and all help welcomed.

This is purely a project of love and learning. 
My first Xbox experiences were in my late teens - early 20s, i am 40 in 2024 and
just purchased a 1.4 XBOX and after seeing the available mods...
Wanted an easy way to tie them all together.
