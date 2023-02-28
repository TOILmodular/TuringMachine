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
I added two connectors at the back of the main PCB, where the available Turing Machine expanders "Volts" and "Pulses", available at Thonk, can be plugged in. But, the pinouts are not the same, as in the original module. However, they are labelled on the PCB. I wanted to keep the option open for also building those expanders myself in the future.

## Additional Information about specific Components
If you want to use the Gerber files for having PCB manufactured, please note the following information about components used.

- The design makes use of the SMD version of the quad op amp TL074. Any other SMD quad op amp with the same pinout should work, as well, e.g. UPC824.
- There is another SMD dual op amp, NJM4580. Again, any dual op amp with the same pinout (TL072) is ok.
- There is a number of SMD 0.1uF capacitors with the package size 1608.
- In order to save space, I am always using small size resistors, about 3mm length, which are about half the size of usually used resistors.

![Turing](https://user-images.githubusercontent.com/97026614/221758785-69de212a-b5b8-4ff7-9343-e28fad714d6f.jpeg)

![TuringFront](https://user-images.githubusercontent.com/97026614/221758808-d154555d-97cd-454e-9f06-6e4db8591b59.jpeg)

![TuringSide](https://user-images.githubusercontent.com/97026614/221758857-b8c51a65-e0ad-42c4-bc00-813111f062e1.jpeg)

![TuringBack](https://user-images.githubusercontent.com/97026614/221758887-3ddd8c00-ff24-4655-8663-e6223f47ab9b.jpeg)

<img width="336" alt="MainBoard_Back" src="https://user-images.githubusercontent.com/97026614/221758911-35d8d2e6-5c62-4f97-8076-ba19598b7cc0.png">

<img width="336" alt="MainBoard_Front" src="https://user-images.githubusercontent.com/97026614/221758936-cf6d29cc-3da9-480b-b862-7ff5158076d1.png">

<img width="336" alt="CtrlBoard_Front" src="https://user-images.githubusercontent.com/97026614/221758979-5d773556-781f-428d-92fc-d1926306a6e9.png">

<img width="336" alt="CtrlBoard_Back" src="https://user-images.githubusercontent.com/97026614/221759007-023e2593-9a0d-4cf0-ad3f-c49036a7d130.png">
