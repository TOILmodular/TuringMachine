# Turing Machine - Random Sequencer Eurorack Module
This is my DIY version of the well-known Turing Machine Eurorack module from Tom Withwell - Music Thing Modular, a random looping sequencer.

## Module Build and PCBs
If you want to build the module yourself, I uploaded the schematic, the BOM and the Gerber files for the PCB.

I used several SMD components for op amps and bypass caps.

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created a version with footprints for those components.

The rotary switch component is also different in the two versions. In the "original" version of the PCBs, the rotary switch is from Cosland, part no. RS-2688-0112-38N. While the part used in the "Thonk" version is the one available from Thonk specifically for their Turing Machine kit, part no. SR1712F-0108-20F0A-N9.

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.
I cannot guarantee, if this set of zipped Gerber files works also for other providers, like e.g. PCBWay. I have not tried that. But I saw online, that others did it.

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, referring to the component layout in the Gerber files. The layout is the same for both versions.

## Calibration
The calibration procedure is explained in [this video](https://vimeo.com/163160088). Different from the original module from Music Thing Modular, the trim pot in my version is not accessible from the front panel, but located at the backside of the module.

## Extension Connectors
I added two connectors at the back of the main PCB, where the available Turing Machine expanders "Volts" and "Pulses", available at Thonk, can be plugged in. The pinouts are the same, as in the original module.

## Additional Information about specific Components
If you want to use the Gerber files for having PCB manufactured, please note the following information about components used.

- The design makes use of the SMD version of the quad op amp TL074. Any other SMD quad op amp with the same pinout should work, as well, e.g. UPC824.
- There is another SMD dual op amp, NJM4580. Again, any dual op amp with the same pinout (TL072) is ok.
- There is a number of SMD 0.1uF capacitors with the package size 1608.
- In order to save space, I am always using small size resistors, about 3mm length, which are about half the size of usually used resistors.
