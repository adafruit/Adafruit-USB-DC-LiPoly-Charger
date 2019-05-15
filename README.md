# PCB for the Adafruit USB/DC Lithium Ion/Polymer charger

<a href="http://www.adafruit.com/products/280"><img src="assets/image.jpg?raw=true" width="500px"></a>

This is the PCB for the Adafruit USB/DC Lithium Ion/Polymer charger
__Format is EagleCAD schematic and board layout__

Charge your single-cell lithium ion/polymer battery any which way you like with this board. Have a USB connection? No problem, just plug into the miniUSB connector. Only have a wall adapter? Any standard 2.1mm DC adapter which puts out 5 to 12VDC will work fine. If both are plugged in, the charger will automatically choose whichever has the highest voltage.

Other nice things about this charger include multiple LEDs for power & charging status, including a charging LED which will blink when the battery is full. If the charger gets too hot from high-speed charging, it will slow down the charge rate automatically. You can easily adjust the charge rate up to 1.2A or down to 100mA.

For use with Adafruit Lipoly/LiIon batteries only! Other batteries may have different voltage, chemistry, polarity or pinout.

- Use USB or DC power - 5 to 12V input
- Charges one single-cell 3.7/4.2v batteries (not for older 3.6/4.1v cells) with constant current/constant voltage
- Three indicator LEDs - green for Power, orange for charging and red for error
- Charging LED will blink when the battery is full
- You don't have to worry about heat dissipation in the charger, even when plugging in a 12V DC power jack - thermal protection inside will slow down the charge rate to prevent damage
- 2 JST connections so you can keep the battery plugged in and powering your project
- Terminal block connections galore (if you don't like JST connectors) just solder in 3.5mm terminal blocks
- Default charge rate is about 500mA, but you can easily change this by soldering in a through-hole resistor on. The chip can do 100-1200 mA charging
- Safety timer will stop charging after about 14 hours
- The chip supports a standard 10K thermistor, which we have stuffed as a standard resistor. You can solder in a thermistor easily
- [Lots of information in the datasheet for the MCP73861](http://www.microchip.com/wwwproducts/Devices.aspx?dDocName=en020210)
- Fully assembled, tested and comes with a free JST cable
- [Schematic available for your perusal](https://www.adafruit.com/datasheets/mcp73861.png)
- Dimensions: 1.75" x 1.6"

## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Adafruit Industries.  
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
