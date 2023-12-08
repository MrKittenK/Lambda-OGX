# Lambda-OGX
A single board solution to combine several Original XBOX modifications. OpenXenium/OGX360/BlueRetro/spi2par2019/Wireless Bridge/<?HDMI/>

The plan is to have all componants on one single board with flat ribbon cable/pcb conections to the motherboard.
These will make soldering to the various points on the XBOX motherboard much easier much easier.

These will be soldered to the LPC, USB 1-4, Power, Ethernet and possibly the video chip for HDMI.

5 x ATmega 32U4 
2 x ESP32
1 x FPGA
1 x 1MB-2MB ROM for Bios Banks
1 x Ethernet to Wireless Bridge (Chip\IC\IP)
<?1 x ADV7511?>
(Plus aditional support circitry)

<?Possible addition of HDMI mod?>

4 ATmega 32U4 are used for OGX360
1 ATmega 32U4 is used for spi2par2019
1 ESP32 is used for BlueRetro and comunication with OGX360
1 ESP32 is used for linking all together and possible wifi?
1 WiFi to Ethernet adapter (Possible use of ESP32?)
1 FPGA is used for OpenXenium
<?1 ADV7511 to take video to HDMI?>

1 PCB to add all of these together. 

RGB that can tie into the spi lines of the OpenXenium? 
WLED? 

Use as many existing internal conections as is possible. 

Why?

Simple, I want to make an Ultra Slim OG-XBOX. To do this i will be removing the DVD drive, adding in a 2.5" storage solution (ide to sata adapter). 
Removing the front controller ports, with the combination of BlueRetro and OGX360 I will be able to use a DS4 pad or an XboxOne pad etc etc. 
As such I will have zero need for plug-in controllers.

In making the Ultra Slim I shall be trying to also provide a custom power supply with regulators etc. 
All Capacitors to be replaced with Solid state caps. but these wont be part of Lambda-OGX, just a cap replace. 

If it is possible to tie each mod together with a custom pre-bios I shall try. 
I know that a few solutions already exist provide a pre enviroment for settings / mod configuration. 

Any and all help welcomed.

This is purely a project of love and learning. 
My first Xbox experiences were in my late teens - early 20s, i am 40 in 2024 and just purchased a 1.4 XBOX and after seeing the avaliable mods...
Wanted an easy way to tie them all together.
