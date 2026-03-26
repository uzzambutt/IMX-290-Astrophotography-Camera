# IMX-290-Astrophotography-Camera
> Its a custom astro imaging camera using the IMX 290-IR CUT Sensor connected to a Raspberry Pi zero W2 as the onboard computer.

***There is NO Firmware needed for this camera as its software controlled. Check /Firmware/readme.md for download link for the software.***

## Features
```
1: Uses Sony IMX290 IR-CUT Imaging sensor
2: Features active cooling to keep the computer and especially the camera sensor cool
3: Has an inbuilt Computer to streamline the image processing 
4: Uses OTG to connect to an external computer for live preview
```

## Working
```
1: Sensor Tray: its used to hold the camera sensor to the front of the camera nozzle so the camera stays fixed.
2: Body: used to hold the computer and Sensors together.
3: Back ring: used to hold the back plate to the body.
4: Back Plate: used to hold the 30mm fan for active air cooling.
```
## Usage Instructions 
```
1. Connect the raspberry Pi to a computer via an OTG cable.
2. Install sharpcap on computer and connect your camera with it.
3. enjoy live video feed!
```

## Assembly
```
1. Take the camera tray and insert the IMX 290 Camera with its connector facing towards the FPC cable slit.
2. Screw the camera down via the back side with any available screws
3. Take the FPC cable and insert it from the outside into the camera connector.
4. Glue the camera tray onto the nose tube with the exposed camera sensor being exactly in the middle of the tube.
5. connect the FPC cable with the Raspberry Pi Zero.
6. Take the Active cooling fan and screw it on the backplate with the wires going inwards.
7. Connect the Fan wires to the raspberry pi via any GPIO pin.
8. Pass an OTG cable from the backplate Cable Slit and connect it to the RPi MicroUSB
9. Glue on the Backplate ring and along with it the backplate too.
```

## Images
Sensor Holding Plate:
![img](https://github.com/uzzambutt/IMX-290-Astrophotography-Camera/blob/main/src/image_2025-12-08_142417553.png)

Sensor Holding Plate Top:
![img](https://github.com/uzzambutt/IMX-290-Astrophotography-Camera/blob/main/src/image_2025-12-08_142448654.png)

Camera Enclosure Back Plate:
![img](https://github.com/uzzambutt/IMX-290-Astrophotography-Camera/blob/main/src/image_2025-12-08_142425061.png)

Enclosure Side:
![img](https://github.com/uzzambutt/IMX-290-Astrophotography-Camera/blob/main/src/image_2025-12-08_142432265.png)

Enclosure Front/Top:
![img](https://github.com/uzzambutt/IMX-290-Astrophotography-Camera/blob/main/src/image_2025-12-08_142440306.png)

Wiring Diagram:
![img](https://github.com/uzzambutt/IMX-290-Astrophotography-Camera/blob/main/IMG_20260221_164848.jpg)

BOM:

| Item_ID | Part_Number | Description | Quantity | Unit_Cost_Estimate | Total_Cost_Estimate | Manufacturer_Supplier |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | IMX290-MOD | Sony IMX290 Camera Module | 1 | 40.00 | 40.00 | [AliExpress](https://a.aliexpress.com/_c2QmWf2P) |
| 2 | SC0352 | Raspberry Pi Zero 2 W | 1 | 15.00 | 25.00 | [AliExpress](https://a.aliexpress.com/_c3kVF7KJ) |
| 3 | HS-RPi-Z2 | Heatsink for Raspberry Pi Zero 2 W | 1 | 5.00 | 3.00 | Generic |
| 4 | FAN-30MM-5V | 30mm x 30mm x 7mm 5V DC Fan | 1 | 5.00 | 5.00 | Generic |
| 5 | CABLE-CAM-FPC | FPC or equivalent cable/connector | 1 | 3.00 | 3.00 | [AliExpress](https://a.aliexpress.com/_c3RoJItt) |
| 6 | SD-16GB-C10 | MicroSD Card 16GB Class 10 | 1 | 8.00 | 8.00 | SanDisk/Samsung |


*(Items dont have links because these are general items and the individual price is already in the screenshots. everyone knows the prices for these already)*


Made for the blueprint submition: [Blueprint](https://blueprint.hackclub.com/projects/5563)
