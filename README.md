##OpenIPC Install##

Support Wyze and Xiaomi Fang Cams

##Installation Instructions:##

1. Download and install Etcher or Win32 Disk Imager
2. Write the openipc_firmware-v0.2.2.img to your SDcard
3. Open the SDCard and edit the files .wifissid and .wifipasswd to match your network
4. Flash the firmware to the camera:

    Hold down the setup button for 10 seconds BEFORE connecting power
    With button still depressed, plug in power to the camera and continue to hold for another 10 -12 seconds and wait until the connection light blinks continually.
    Press setup button and you should hear a Chinese voice prompt if successful.

6. Reboot camera and reinsert SDcard after boot
7. Repeat step 6
8. Run openipscan.sh and find the IP address of your new OpenIP Camera. Note: MAC address will be changed to c0:6d:1a*
9. Proceed to the status web page and apply the hacks. http://ipaddresshere/cgi-bin/status *NOTE: of you get a 404 error with a flashing blue led, Remove the sdcard and reinsert it. Shortly after thst the camera will go "click click" again. Proceed to the link now*

Congratulations! Welcome to OpenIPC.

RTSP: 
rtsp://ipaddress/unicast

SSH:
root/ismart12


Thanks to samtap for fanghacks used as the base for OpenIPC. Thanks to joeand37 for inspiration. Thanks to the various other developers on the fanghacks page who cross-compiled some of the binaries.
