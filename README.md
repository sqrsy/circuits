# What is it?

This folder contains Eurorack modules (PCBs and panels) that I designed. They are all open to use, but you must make any derivatives open too. If you use them commercially, please donate 10% of profits to a charity nearby you.

I will add detailed part lists and assembly instructions if and when I make them.

# Modules

* cv-mixer: uses an op-amp to perform attenuversion and addition on 3 inputs.
	* Parts: thonk jacks, thonk 50k pots, {560, 100k, 1M} resistors, 0.1 uF capacitors, tl074 op-amps, 10-pin power.

* logic: two sets of 2-input, 3-output logic gates: or, and, xor.
	* Parts: thonk jacks, {5k, 150k} resistors, 3mm LEDs, 4030 IC, 4071 IC, 4081 IC, 16-pin power.
	* Note: this is an imperfect module. It is missing an input comparator and an output buffer, and has untied pins on the unused logic gates.

* rasa3x2: a generic 2-input, 6-parameter, 4-switch, 2-output Arduino Nano Every Eurorack module shield with DAC and optional negative voltage output.
	* Parts: thonk jacks, thonk 50k pots, thonk switches (optional), {330, 500, 1k, 10k, 20k, 100k} resistors, 3mm LEDs, mcp4822, 16-pin power.

* rasa6: a generic 1-input, 2-parameter, 2-output Arduino Beetle Eurorack module shield with optional DAC.
	* Parts: thonk jacks, thonk 50k pots, {150k, 220k} resistors, mcp4822 (optional), 16-pin power.

* rectified-mult: a 9-jack mult where 4 of the jacks apply some rectification to the signal.
	* Parts: thonk jacks, 1k resistors, diodes, full-bridge rectifiers, 3mm LEDs.

* sn76489: exposes the sn76489 chip as a Eurorack module.
	* Parts: thonk jacks, thonk 50k pots, thonk sub-mini switch, {150k, 220k} resistors, sn76489, 16-pin power.

* switched-mult: a 9-jack mult that can route a 3-jack mult to one of two different sets of 3-jack mults.
	* Parts: thonk jacks, thonk sub-mini switch.

# Disclaimer

All files are provided without any guarantee. If you notice a mistake, please submit an Issue and I will fix it.