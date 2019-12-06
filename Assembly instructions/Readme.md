**Assembly instructions**

After sourcing the materials described in the BOM start assembling the parts as described in this document.

**3D printed parts**

There are two parts to be 3D printed - the PLA LED block and the Cuvette Holder.

You can use a 3D printer service online or in your local community, or even print it yourself.
If you are going to print it yourself the the recommended settings to 3D print are described in the table 1 (using Ultimaker Cura software).

<i>Table 1 - Main characteristics used to 3D print the Phone Spectrometer</i>

|  Characteristic |  Selection |
|:-:|:-:|
| Layer height  |  0.2mm |
|  Wall thickness |  2mm |
| Top/Bottom thickness  | 0.8mm  |
|  Infill density |  20% |
| Printing temperature  | 210ºC  |
|  Retraction | Enabled  |
| Print speed  | 50mm/s  |
| Generate support  |  No |
|  Build plate adhesion type | Brim  |

Since the 3D printed method is by Fused Deposition Manufacturing the layers are horizontal. This means that the cuvette holder may be fragile at some key parts, and may easily snap. We recommend you to 3D print the cuvette holder horizontally so you have a stronger and much durable part to work with (figure 1).

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/3Dprint_orientation.PNG?raw=true)
<i>Figure 1 - Recommended orientation to 3D print the Cuvette Holder</i>

The recommended material to 3D print is a Traffic Black PLA filament (RAL 9017), from Fillamentum Manufacturing Czech s.r.o. or equivalent. 

**Cuvette Holder**

This part only requires the addition of the rubber part (i.e. figure 2)

<img src="https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/rubber_part.PNG?raw=true" width="200">

<i>Figure 2 - Rubber part to be glued to the cuvette holder.</i>

Use a puncher to do a hole in the middle of the rubber
Glue it tightly aligned to the rear aperture of the cuvette holder so it will stay between the light exit and the phone sensor - as seen in the BOM designators doc.

This rubber will help you align the rear hole with the phone sensor to get the maximum light measurement possible and also limit the ambient light to interfere with the sensor.

**LED Block**

The LED you choose to use depends on the analyte; for instance, you can have several PLA LED Blocks with different LED mounted and so different emission wavelengths.

To mount the LED you have to identify the LED cathode (-) and anode (+) - figure 3.

<img src="https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/LED_scheme.PNG?raw=true" width="200">

Next, mount the LED as specified in figure 4.

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/LED_mount.PNG?raw=true)

<i>Figure 4 - LED mounted in the printed block, with a CR2032 battery. The anode passes trough the right hole to the outside, touching the battery when it is in the down position and the cathode passes in the first hole to the outside and them to the further left hole to the inside of the model, creating a loop.</i>


The two parts - LED Block and Cuvette Holder fit together and the LED goes inside the front aperture of the Cuvette Holder - it may be necessary to adjust the LED position the first time.

**Finish**

After the assembly of the parts, turn on the LED and mount it with the rear hole pointed near the front camera of your phone. Open the Shoebox Spectrophotometer APP, start moving the model checking the light measure to figure when the light gets to the sensor - you should get reading from 0, when the rear hole is completely misaligned, to a big value like 4000 for example (this depends on the sensor of your phone).

<ins>Note:</ins>

If the LED Block have a loose fit to the Cuvette Holder you may use something so it remains stable (such as a little piece of paper between the models, or an elastic rubber). You may even glue it if you don’t intend to change the LED Block.
The LED Block turns on when the coin battery in down and off when the battery is up.
You can use the LED Block turned on to help you glue the rubber part to the Cuvette Holder.
Do not use the APP when the light measurement seams to be at the highest value possible. Move a little the holder so it slightly misalign with the sensor and gets a more variable value so the sensor is not saturated with light.
