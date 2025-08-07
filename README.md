# pi5-slidetop
A Raspberry Pi 5 laptop with a unique sliding and opening hinge. 

The hinge and various other parts of the laptop was inspired by the laptop created by the YouTube channel of 'TecH BoyS ToyS'. Here is a link to his video: https://youtu.be/jntHraUABHo?si=zRmpOkPDyJXu36e1




 Of course there are many differences between his laptop and mine. In fact even the hinges are different, even though my hinge is based off of his. the size is different (since I chose a smaller screen), I am using a camera module, I am also using the Pi5 and not the Pi4, none of the parts in my design are soldered (because I dont know how to solder), and other differences.


WARNING: the 3D models on this repo are not finished. I will post updates and refinements on this repo as I work on this project. I just wanted to get this on GitHub as soon as possible. Also if you dont understand what each 3D model is for and why it is made the way it is, don't worry, your  not meant to. I didn't get around to adding comments and proper schematics and documentation, It is just the CAD files for now.

# Parts

WARNING: I have no affiliation with the sellers which I have linked nor can I confirm their validity. When buying from any of the sellers that I've linked be cautious and do your own research. 

1. I used a 9.7" LCD display. Here is a link to the screen and controller board that I used: https://www.aliexpress.us/item/3256804853009409.html?src=bing&aff_short_key=UneMJZVf&aff_platform=true&isdl=y&albch=shopping&acnt=135095331&isdl=y&albcp=555009888&albag=1306220957358842&slnk=&trgt=pla-4585238373885205&plac=&crea=81638865041502&netw=o&device=c&mtctp=e&utm_source=Bing&utm_medium=shopping&utm_campaign=PA_Bing_US_PLA_PC_Electronic_Max%20Value%E6%94%B9TROAS_20240704_AESupply&utm_content=Electronic&utm_term=9.7inch%20lcd%20screen%20with%20controller%20board&msclkid=c5985899ba16178741bb301492bd51f6&gatewayAdapt=glo2usa
2. I used the Geekworm X1001 PCIe to M.2 Key-M NVMe SSD PIP TOP for the NVMe slot. Here is a link to the seller: https://geekworm.com/products/x1001. I removed the 5V INPUT terminal from the NVMe slot since it was to big to fit.
3. I used an 8 Megapixel 1080P IMX219 Camera Module V2.3 from Arducam as a camera for my laptop. Here is a link to a seller: https://www.amazon.com/Arducam-Raspberry-Megapixel-Compatible-RPI-CAM-8MP/dp/B09V576TFN?source=ps-sl-shoppingads-lpcontext&ref_=bing_fplfs&th=1
4. Since the OEM ribbon cables for the camera module were to short I bought a 500mm ribbon-cable to connect my Raspberry Pi 5 to the camera module. Here is a link to a seller: https://www.amazon.com/Flexible-Raspberry-Suitable-Modules-Connecting/dp/B0CVS264R1/ref=pd_sbs_d_sccl_1_1/142-1785102-2045967?pd_rd_w=cmjYj&content-id=amzn1.sym.2cd14f8d-eb5c-4042-b934-4a05eafd2874&pf_rd_p=2cd14f8d-eb5c-4042-b934-4a05eafd2874&pf_rd_r=8TX35HEF2YEXKB6C1X38&pd_rd_wg=jmWKV&pd_rd_r=bc9d1741-f2a5-4ad5-ba29-1b286ffc12ce&pd_rd_i=B0CVS264R1&psc=1
5. I used a duel speaker setup utilizing a waveshare 2030 Cavity Speakerwith 8Ω and 2W and a 4PIN PH1.25 Connector to connect to the controller board from the display. Here is a link to a seller: https://www.amazon.com/Waveshare-Cavity-Speaker-Compact-Connector/dp/B0D7YLQFWQ/ref=sr_1_2?crid=19IAS0TI4LIYN&dib=eyJ2IjoiMSJ9.yIx3jacncpqtTJGaUn-wxmboyyKEQYYeueNDD-unqxOmA8b_DV3fWfF2y8ul45Pu.vhpMBaZbyKYpvRIUsI0cT-KqKLa7Ta1-VScA8lY_bF4&dib_tag=se&keywords=duel+speaker+20w+waveshare+with+1.25PH+4pin+connecter&qid=1754540357&s=electronics&sprefix=duel+speaker+20w+waveshare+with+1.25ph+4pin+connecter%2Celectronics%2C107&sr=1-2
6. To take advantage of the RPI5's 2nd micro-HDMI slot I used a fairly generic male micro-HDMI to female HDMI cable. I had to cut off the excess padding on either end of the cable to make it fit.
