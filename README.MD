# Flex Cables for V9-V12 PS2


Why? In an attempt to curb piracy, $ony designed the laser to fail and burn up. Sadly this [backfired](https://www.gamesindustry.biz/sony-reaches-settlement-in-ps2-disc-read-error-case#:~:text=Now%20a%20settlement%20has%20been,their%20console%20%2D%20at%20SCEA's%20discretion.)

![Mermaid Chart](/assets/whylaserburns_mermaid.jpg)
Courtesy of [El Isra](https://github.com/israpps)

Invented by the Matrix Team, they designed a cheap and easy fix for V9-V12 PS2s, documented [here](https://github.com/MechaResearch/MechaPwn/blob/master/docs/PICfix.md) and refined by HaloSlayer255 and [ModzvillUSA](https://modzvilleusa.com/products/ps2-matrix-picfix-for-v9-v12-ps2-consoles)


I (R3Z3N) simply applied some artistic touch to make this an easier install that will look professional with decent soldering skills. CLEAN YOUR FLUX BOYS!


### $ony Laser fix identification

If your PS2 is the following model with the circutry in red, you DO NOT NEED THIS FIX!

![Sony Laser Fix](/assets/70k%20laser%20fix.jpg)

### Mechacon Crash Tester App

El Isra made a PS2 app which identifies if your console is safe, unsafe or uknown. Run the ELF on your PS2 with your desired exploit/elf launcher of choice:

[Mechacon Crash Tester](https://github.com/israpps/MechaconCrashTestAPP)

![Mechacon Crash Tester](https://www.psx-place.com/attachments/_e3271012_20240808144428-png.43804/)

### Matrix PicFix Schematic

[PicFix Schematic](assets/PicFix_Schematic.pdf)

## Appreciation and Thanks to:
[Atheris](https://linktr.ee/atherismods), [SylverRez](https://github.com/m4x10187) and [PCM720](https://github.com/pcm720) for kicad, electrical and logo help! [ModzvilleUSA](https://modzvilleusa.com/products/ps2-matrix-picfix-for-v9-v12-ps2-consoles) & HaloSlayer255 for the writeups and schematic.


## Parts Needed

[100nF 0603 Capacitor](https://www.mouser.com/c/passive-components/capacitors/ceramic-capacitors/mlccs-multilayer-ceramic-capacitors/multilayer-ceramic-capacitors-mlcc-smd-smt/?capacitance=0.1%20uF&case%20code%20-%20in=0603&length=1.6%20mm%20%280.063%20in%29&termination=Standard&tolerance=10%20%25&voltage%20rating%20dc=25%20VDC&width=0.8%20mm%20%280.031%20in%29&instock=y&sort=pricing)

[1.5K Ohm 0603 Resistor](https://www.mouser.com/c/passive-components/resistors/smd-resistors-chip-resistors/thick-film-resistors/?case%20code%20-%20in=0603&packaging=Cut%20Tape&power%20rating=250%20mW%20%281%2F4%20W%29~~333%20mW%20%281%2F3%20W%29&resistance=1.5%20kOhms&tolerance=5%20%25&instock=y&sort=pricing&rp=passive-components%2Fresistors%2Fsmd-resistors-chip-resistors%2Fthick-film-resistors%7C~Power%20Rating)

[2.2K Ohm 0603 Resistor](https://www.mouser.com/c/passive-components/resistors/smd-resistors-chip-resistors/thick-film-resistors/?case%20code%20-%20in=0603&packaging=Cut%20Tape&power%20rating=250%20mW%20%281%2F4%20W%29~~333%20mW%20%281%2F3%20W%29&resistance=2.2%20kOhms&tolerance=5%20%25&instock=y&sort=pricing&rp=passive-components%2Fresistors%2Fsmd-resistors-chip-resistors%2Fthick-film-resistors%7C~Power%20Rating)

[PIC 12F508 IC SOIC-8 Package](https://www.mouser.com/ProductDetail/Microchip-Technology/PIC12F508-I-SN?qs=mcPJWgAPNrfwaHSjpX90MQ%3D%3D)

Pic 12F508 files, choose based on your programmer:

[MFIX_H8.HEX](/assets/MFIX_H8.HEX)

[MFIX_H16.HEX](/assets/MFIX_H16.HEX)

## Programming PIC12F508

Tutorial incoming....sorry. If you'd like to help please reach out!


## V9 Flex

Waiting for V9 PCB to design one


## V10 Flex

[V10 Flex Gerbers](/SCPH-500XX/GH-026/V10%20SCPH-500XX%20GH-026%20PicFix%20Flex%20GERBERS.kicad_pcb.zip)

[BOM File](/SCPH-700XX/SCPH-700XX%20PicFix%20Flex%20BOM.csv)

![GH-026 Flex Front](/SCPH-500XX/GH-026/V10%20SCPH-500XX%20GH-026%20PicFix%20Flex.png)

![GH-026 Flex Rear](/SCPH-500XX/GH-026/V10%20SCPH-500XX%20GH-026%20PicFix%20Flex%20REAR.png)

The below PCB is for experts only, as soldering to the DSP may be quite difficult:

![GH-026 Flex Rear](/SCPH-500XX/GH-026/V10%20SCPH-500XX%20GH-026%20PicFix%20Flex%20REAR%20EXPERT%20SOLDERING.png)

![GH-026 Flex Front](/SCPH-500XX/GH-026/V10%20SCPH-500XX%20GH-026%20PicFix%20Flex%20EXPERT%20SOLDERING.png)


## V12 Flex

[V12 Flex Gerbers](/SCPH-700XX/SCPH-700XX%20PicFix%20Flex%20GERBERS.zip)

[BOM File](/SCPH-700XX/SCPH-700XX%20PicFix%20Flex%20BOM.csv)

![V12 Flex Front](/SCPH-700XX/PicFix_V5_Thin.png)

![V12 Flex Back](/SCPH-700XX/PicFix_V5_Thin%20back.png)