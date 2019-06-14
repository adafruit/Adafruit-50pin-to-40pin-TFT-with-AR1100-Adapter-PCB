## Adafruit 50pin to 40pin TFT with AR1100 Adapter PCB
<a href="http://www.adafruit.com/products/3305"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop
</a>

PCB files for the Adafruit 50pin to 40pin TFT with AR1100 Adapter
- https://www.adafruit.com/product/3305

Format is EagleCAD schematic and board layout

This is a very special adapter, specifically used for adapting our RTD266X driver boards that have 50-pin TFT connectors to use 40-pin TFTs. Please note the adapter cannot be used the other way around! As an addition, we add in an AR1100 resistive touch controller.

Resistive touch screens are incredibly popular as overlays to TFT and LCD displays. If you want to connect one to a computer you need something to handle the analog to digital conversion. Most converters we've found are not very easy to use, and are 'fixed' - making them difficult to calibrate. The AR1100 is a nice chip that solves this problem by acting as a touch->USB converter and also comes with calibration software. The calibration software is Windows only, but once you've calibrated you can use the screen on any OS. The AR1100 shows up as a regular Mouse or Digitizer HID device so no drivers are required and it works on any operating system that supports a USB mouse.

These are sold with our test calibration, you may need to calibrate yourself which you can do with the Microchip windows software. For more details including calibration software, check out the AR1100 page. Once you've got video working, when you plug into a computer's USB port you should see a new device and touching the screen will cause the mouse cursor to move around.

This adapter is for advanced users only!

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit.com](https://www.adafruit.com)!

See license.txt for more information.

Creative Commons Attribution, Share-Alike license, check license.txt for more information 
All text above must be included in any redistribution
