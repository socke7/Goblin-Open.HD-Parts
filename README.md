# Goblin-Open.HD-Parts
A retractable nose camera setup for Open.HD on a STRIX Goblin

## References
You dont't know what Open.HD is? Read more [here](https://openhd.gitbook.io/open-hd/).<br>
Never heard about the STRIX Goblin? Look [here](https://www.readymaderc.com/products/details/strix-goblin-high-performance-fpv-plank-pnp).<br>
## Credits
This project is based on the nice Goblin nose scan by user billyd60 at [rcgroups](https://www.rcgroups.com/forums/showpost.php?p=46243363&postcount=3574).<br>
## Motivation
One of the best cameras available at the moment for Open.HD are the Veye IMX290/307/327 MIPI/CSI cameras. They have many useful features for FPV, like WDR and an excellent low light sensitivity - also they come with a high quality lens. A disadvantage is their price, so it was mandatory for me to handle my camera with care. That gave me the idea to make the camera retractable to better protect it in case of crashes or hard landings.
## How it works
This is how it looks from outside:<br>
![](/media/outerview.gif)<br>
Everything is controlled by a simple servo:<br>
![](/media/innerview.gif)
## Shopping list
* one of these cameras: [MIPI-CAM-290-ISP](https://www.inno-maker.com/product/mipi-cam-290/), [MIPI-CAM-307-ISP](https://www.inno-maker.com/product/mipi-cam-307/), [MIPI-CAM-327-ISP](https://www.inno-maker.com/product/mipi-cam-327/)
* Raspberry Pi 3A+
* Servo EMAX ES08MAII
* 6 pcs cylinder head screw DIN912 M3x8
* 3 pcs cylinder head screw DIN912 M2x6
* 2 pcs hex nut DIN934 M3
* hex nut DIN934 M2
* 4 ps Nylon hex spacer M2 for mounting the camera - length was 6mm in my case, but may be different for other lenses
* 8 or 12 pcs Nylon hex spacer M2.5 for mounting the Pi
* a stripe of double sided tape for attaching the Pi Mount to the bottom of the fuselage
## Print the parts
Download the stl files from [here](/stl/), I recommend printing the parts with PETG using this settings:
* Nozzle: 0.4mm
* Extrusion Width: 0.5mm
* Layer Height: 0.2mm
* Infill: 30% for NoseMount.stl, other parts 100%
* Support is needed for CameraMount.stl only.
## Assemble
This picture should make clear how to assemble everything:<br>
![](/media/assembly.png)
## Integrate
Of course you can control the servo directly from your RC transmitter. But if you have a Flight Controller running Arduplane you could use the [Landing Gear/ Retractable Camera Mount](https://ardupilot.org/plane/docs/common-landing-gear.html) feature!
## Have fun!