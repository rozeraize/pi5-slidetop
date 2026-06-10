# pi5-slidetop
A Raspberry Pi 5 laptop with a unique sliding and opening hinge. 





 Of course there are many differences between his laptop and mine. In fact even the hinges are different, nevertheless my hinge is still based off of his. the size is different (since I chose a smaller screen), I am using a camera module, I am also using the Pi5 and not the Pi4, none of the parts in my design are soldered (because I dont know how to solder), and there are other differences which I won't bother to mention here.


WARNING: the 3D models on this repo are not finished. I will post updates and refinements on this repo as I work on this project. I just wanted to get this on GitHub as soon as possible. Also if you dont understand what each 3D model is for and why it is made the way it is, don't worry, your  not meant to. I didn't get around to adding comments and proper schematics and documentation, It is just the CAD files for now.

# Parts

WARNING: I have no affiliation with the sellers which I have linked nor can I confirm their validity. When buying from any of the sellers that I've linked be cautious and do your own research. 

# used a 9.7" LCD display.
Display: 
1. Display Area：196.608(W)×147.456(H) mm
2. Outline Size：208.88(W)×167.12(H) mm
3. Panel Model:LP097QX1-SPC1
4. Panel Type:a-Si TFT-LCD , LCM
5. Bezel Opening：201.01(W)×151.86(H) mm
6. Panel size:9.7 inch
7. Resolution：2048(RGB)×1536 , QXGA

Display Controller board: 
1. HD LCD Controller Board VS-RTD09705-V1
2. Board Size: 120mm x 62.5mm x 5mm
3. Audio Output: Earphone Support Speaker 4ohm 2W or 8ohm 1.5W
4. Video Input: Mini HD HD Version 1.4 Mini HD
# Other Parts
6. Input Power Supply: DC Connector 3.5mmx1.35mm 5~12Vdc Mirco USB 5Vdc
3. I used the Geekworm X1001 PCIe to M.2 Key-M NVMe SSD PIP TOP for the NVMe slot.  I removed the 5V INPUT terminal from the NVMe slot since it was to big to fit.
4. I used an 8 Megapixel 1080P IMX219 Camera Module V2.3 from Arducam as a camera for my laptop. 
5. Since the OEM ribbon cables for the camera module were to short I bought a 500mm ribbon-cable to connect my Raspberry Pi 5 to the camera module. 
6. I used a duel speaker setup utilizing a waveshare 2030 Cavity Speaker it has 8Ω and 2W and a 4PIN PH1.25 Connector to connect to the controller board from the display. 
7. To take advantage of the RPI5's 2nd micro-HDMI slot I used a fairly generic male micro-HDMI to female HDMI cable. I cut off the excess padding on either end of the cable and replaced the it with electric tape in order to make it fit.
