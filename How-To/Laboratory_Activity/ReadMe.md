# Laboratory Activity

<ins>Objectives</ins>

**- Lambert-Beer Law verification**

**- Sample Assay**

## Lambert-Beer Law verification

For the experimental activity we will need access to a spectrophotometer and to one or more sets of coloured filters. One can use professional materials or, in this case:

- An Android phone with an ALS (ambient light sensor) and the APP “Shoebox Spectrophotometer"

- Spectrophotometer and light source (fixed wavelength from a LED) made by 3D printing or other creative method.

- Coloured filters with 9mm x 30mm.


![alttext](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/How-To/Laboratory_Activity/Activity_assets/Figure%201.jpg?raw=true)
*Figure 1 - Fixed wavelength spectrophotometer and filters used*


When using LEDs we assume the wavelengths in the table 1.

*Table 1 - Maximum emitted wavelength of coloured LED*
|LED   |Emitted Wavelengh (max)|
|------|-----------------------|
|Red   |625nm                  |
|Green |525nm                  |
|Blue  |465nm                  |
|Orange|610nm                  |
|Yellow|575nm                  |

### Procedure

1. Mount the spectrophotometer with the LED turned on and with the APP launched.

2. Adjust the equipment until you obtain a LUX reading that is high.

3. Register the approximate value of the LUX measured and take note of this value as you add filters to the spectrometer.

### Data Processing

Assuming that the first value of LUX corresponds to 100% of transmittance, start to calculate the percentage of transmittance of each filter assuming the  previous LUX measure.

#### Questions to be answered:

> All the filters give us the same percentage?
> 
> What can we say about the linearity needed for the Lambert-Beer Law?
_____

**Lets start with this example:**

We used a LED of 525nm (green) and started adding yellow filters. The LUX data are in the table 2.

*Table 2 - Data obtained at 525nm for yellow filters*
|Number of Filters|Lux  |
|-----------------|-----|
|0                |13150|
|1                |9830 |
|2                |7580 |
|3                |5640 |
|4                |4540 |
|5                |3630 |
|6                |2850 |

Next we processed the data in order to understand if we maintain the linearity - if one filter gives us an aberrant reading - out of the expected percentage.

We can check in table 3, that for each new filter added our source loses about 20-25% of intensity. We can say that we must have linearity since the values are in the same order of magnitude.

*Table 3 - % of transmitance for each added filter*
|Number of Filters|% Transmitance|
|-----------------|--------------|
|0                |100           |
|1                |75            |
|2                |77            |
|3                |74            |
|4                |80            |
|5                |80            |
|6                |79            |


After the analysis we can observe the transmittance as we add each filter. The table 4 presents the data expressed in the graphs 1 and 2.


*Table 4 - % of transmitance and absorbance with increased number of added filter*
|Number of Filters|% Transmittance|Absorbance|
|-----------------|---------------|----------|
|0                |100            |0         |
|1                |75             |0,13      |
|2                |58             |0,24      |
|3                |43             |0,37      |
|4                |35             |0,46      |
|5                |28             |0,56      |
|6                |22             |0,66      |


![alttext](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/How-To/Laboratory_Activity/Activity_assets/Graph1_2.jpg?raw=true)
*Graph 1 and 2 - Transmitance and absorbance versus number of filters*


We have here an experimental evidence that the transmittance decreases in a logarithmic fashion and the absorbance remains linear. We will check next what happens in a linearity loss case.

_____

With the same light source we tested pink coloured filters.

The data obtained and its processing are condensed in the table 5. We can observe that the percentage of the retained radiation for each filter is very inconsistent.

*Table 5 - Data obtained and processed of the pink filters at 525nm*
|Number of Filters|LUX  |%Transmitance/Filter|%Transmitance|Absorbance|
|-----------------|-----|--------------------|-------------|----------|
|0                |12500|100                 |100          |0         |
|1                |368  |2,9                 |2,9          |1,5       |
|2                |33   |9                   |0,3          |2,6       |
|3                |14   |42,4                |0,1          |3         |
|4                |10   |71,4                |0,1          |3,1       |
|5                |6    |60                  |0            |3,3       |
|6                |6    |100                 |0            |3,3       |

By this analysis we notice that the absorbance is not linear with the number of filters added but more like logarithmic.

One indicator of a good linear regression is a R<sup>2</sup> close to, or higher than 0,9, which is not the case here.

Note that in visible spectroscopy the usual values of absorbance are less than 1 AU, to minimize the effects of light dispersion and loss of linearity.

![alttext](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/How-To/Laboratory_Activity/Activity_assets/Graph3_4.jpg?raw=true)
*Graph 3 and 4 - Transmitance and absorbance of pink filters at 525nm*

_____

## Sample Assay

### Indigo Carmine in blue Pills

<ins>Notice:</ins> This procedure is only a demonstration and can be used for any coloured sample, using the right wavelength.

> How do we choose the wavelength with which we will analyse a sample?

	We want to minimize the error and use a typical maximum of the spectrum of the analyte.
	For that we need the molecule spectrum from bibliography or experimentally obtained.
	We used the literature available online to check the best wavelength to analyse the blue pills.
	To analyse the Indigo Carmine present in the blue pills we choosed the 625nm LED (red), that is close enough to the molecule maximum of 610nm.

![alttext](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/How-To/Laboratory_Activity/Activity_assets/Figure%202.jpg?raw=true)
*Figure 2 - Absorbance spectra of Indigo Carmine; Bentouami, Abdelhadi & Said Ouali, Mohand & de menorval, Louis-Charles. (2015). 1-s2.0-S1010603010000894-main.*

> To proceed with the assay, is it only needed to obtain the pills absorbance?

	No. We will also need to compare the obtained absorbance with a reference standard.

_____

### Remembering the Lambert-Beer Law
A = 𝓔bc
If we know the value of 𝓔 at the wavelength we are using, theoretically we only need the absorbance. But in our case we don’t know for sure that value, and to minimize the errors in our analysis we need to perform a calibration curve with a standard of known concentration.

**To this work we need:**
- Test tubes
- 5 Volumetric flasks of 20,0 ml and one of 100,0 ml
- Micropipette and volumetric pipetts
- Scale
- Cuvettes
- Deionised water
- Indigo Carmine Standard
- Filters of porosity <0,45 µm


### Procedure
1. Weight 100 mg of standard to the 100,0 ml volumetric flask and dilute with water.
2. Disintegrate 10 pills in 10,0 ml of water, and filter.
3. Measure 250 µl, 500 µl, 1 ml, 2 ml and 3 ml of the standard to each volumetric flask of 20,0 ml and add water.
4. Measure the absorbances of the standards and the sample with the APP Shoebox Sectrophotometer using water as blank.
5. Make a calibration curve with the standards and determine the concentration of blue colorant per pill.

### Results
From developing the linear regression equation obtained to the sample absorbance we conclude that each pill have 0,45 mg of indigo carmine colorant (see table 6 and graph 5).
This work can also be applied to drinks, candies, and everything that have colour.

*Table 6 - Absorbances measured for 102,0mg of standard and sample*
|Concentration mg/mL|Absorbance|
|-------------------|----------|
|0                  |0         |
|0,1275             |0,08      |
|0,255              |0,139     |
|0,51               |0,268     |
|1,02               |0,444     |
|1,53               |0,637     |
|Sample             |0,211     |

![alttext](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/How-To/Laboratory_Activity/Activity_assets/Graph5.jpg?raw=true)
*Graph 5 - Calibration Curve*
