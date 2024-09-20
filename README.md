# AMC3302
A three-phase current detection circuit based on TI AMC3302.

The AMC3302 is a ±50-mV input, precision current sensing, reinforced isolated amplifier with integrated DC/DC.
## Fixed Gain 41
## Excel Calculator
TI Isolated Amplifier Current Sensing Excel Calculator can be found [here](https://www.ti.com/tool/download/SBAR020).
# LT3045
20V, 500mA, Ultralow Noise, 
Ultrahigh PSRR Linear Regulator.
The output voltage is set by a resistor, $R_{set}$ according to the following formula:
|$V_{out}$|$R_{set}$|
|:---:|:---:|
|2.5V|24.9kΩ|
|3.3V|33.2kΩ|
|5V|49.9kΩ|


# Design details
- Shunt resistor:    1mΩ
- Power supply:  5V-15v
- Output voltage of LT3045: 3.3V
- Vref: 1.65V
- Vout range: 0-3.3V
- Current range: -40.24A---+40.24A
- Overall gain: 24.3902439 V/A


$I = \frac{V_{out}-V_{ref}}{41*R_{shunt}}$

## Reference datasheets
- [AMC3302](https://www.ti.com/product/AMC3302)
- [LT3045](https://www.analog.com/media/en/technical-documentation/data-sheets/3045fa.pdf)