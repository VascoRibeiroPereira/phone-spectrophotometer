# Enhancement Issue - Adding a Resistor

Issue Link: https://github.com/VascoRibeiroPereira/phone-spectrophotometer/issues/6


Note: this file explains how to add a resistor to the original design. If you want to avoid this procedure you can buy an LED with incorporated resistor like this: https://www.sparkfun.com/products/14560


This issue was considered an enhancement that is not crucial for the use of the phone spectrophotometer but highly beneficial.

The benefits to it's use are mainly:
<ul>
  <li>Prevent the LED from shorts</li>
  <li>Stabilize the current</li>
</ul>



The % of light loss at the beginning of turning on the equipment is ameliorated, as seen in the next graph:

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/LEDVsResistot.jpg?raw=true)


To apply this enhancement we need to calculate the resistor value, for that we need the Ohm's Law:

<b>R = V / I</b>

Gather this information from your LED:
<ul>
  <li>Forward Voltage drop (Vf) in V </li>
  <li>Max Current (I) in A</li>
</ul>

For example, the Super Bright Red LED from Sparkfun: https://www.sparkfun.com/products/528

Vf = 2,4V <p>
I = 0,02A

If we supply 3V (Vs) from our CR2032 battery, then:

V = Vs - Vf = 3 - 2,4 = 0,6 V

Applying Ohm's Law:

R = 0,06 / 0,02 = 30 Ω

It is needed a resistor as close to 30 Ω as possible. This process must be done to every LED from different wavelengths and manufacturers (because they may differ in characteristics).

<b>How to mount?</b> Simply soldering it to the anode of the LED and use the other end of the resistor as the anode that touches the battery.


![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/LED.jpg?raw=true)<p>
LED without resistor

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/LED_Resistor.jpg)<p>
LED with resistor

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/LED_Block_Resistor.jpg?raw=true)<p>
LED with resistor mounted in the LED Block

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/Assembled.jpg?raw=true)<p>
The LED block + Cuvette block mounted in the resistor version without issues.

3D Planed...

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/images/Planed_Block.jpg?raw=true)<p>

<b>Personal notes from the author:<p>
I never experience a short from using the described materials - CR2032 battery - with any LED. If anyone experience it, please open an issue and I will include the resistors as part of the design!</b>
