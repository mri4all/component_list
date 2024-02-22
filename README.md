# Components List for MRI4ALL Zeugmatron Z1

> [!IMPORTANT]
> The list of components is still being updated and incomplete. We will also try to add supplier information.

## Housing

<p align="center">
  <img src="https://github.com/mri4all/components_list/assets/35747793/cac7e881-dc4a-4fe2-9eb4-8a4c13933e37" width="550"/>
</p>

* 3D-printed parts from provided STL model (TODO: Add link to 3D model)
* Requires high accuracy 3D printer, e.g. Statasys F370
  
> [!NOTE]
> Costs for 3D-printing all needed parts are signficiant (~ $8k)

## Magnet

* 1000 N40UH magnets, 12.7 x 12.7 x 12.7 mm (TODO: add supplier)
* 300 N40UH shim magnets, 3mm (TODO: add supplier)
* Plastic screws to combine magnet rings (TODO: add screw types)

## Field Mapper

* 3D CNC rail set up (3x 30 cm linear CNC stages attached perpendicularly, brand: FUYU, source: Amazon)
* Arduino UNO Rev3 (https://store.arduino.cc/usa/arduino-uno-rev3)
* Arduino gShield (https://synthetos.com/project/grblshield)
* Hall probe (Metrolab THM1176 used here, USB connection, https://www.metrolab.com/products/thm1176-three-axis-hall-magnetometer/)
* Rod for connecting Hall probe to guide
* Control computer (Ubuntu 20.04 / Windows 10 or 11)
* Field mapping software (https://github.com/mri4all/field_mapper_3DFM)

## Gradients

* 3D-printed wire holders with imprints
* Enameled copper wire for gradients (TODO: add specs)
* Superglue, epoxy, Kapton tape
* Gradient Power Amplifier GPA-FHDO (https://github.com/menkueclab/GPA-FHDO)
* DAC-Hat for Red Pitaya board (TODO: add source)
* Powersupply for GPA, needs DC 15V and 40A (e.g. Rohde & Schwarz HMP4040 (~ 3k) or TekPower TP1560E DC for ~ $400)
* DC feedthrough capacitor for filtering gradient waveforms (6 x Schaffner FN7563-63-M6, https://www.mouser.com/ProductDetail/Schaffner/FN7563-63-M6?qs=m2s1G0dHrOR4GHqM%252B%252BtiCA%3D%3D)
* Holder for filter capacitors
* Depending on local power quality: Power conditioner (e.g., Furman Elite-15i)
  
## RF Hardware

* Wire and components for RF coil (TODO: add specs)
* RF preamp (TODO: add model)
* Power supply for RF preamp DC, 15V 2A (e.g., Agilent E3610A)
* RF power amplifier (TODO: add model currently used)

## Scanner Control

* Red Pitaya SDRLab 122-16 (https://redpitaya.com/product/sdrlab-122-16-standard-kit/)
* Computer with Ubuntu Linux 22.04 LTS (e.g., Dell Optiplex 7010 Micro)
* Additional USB ethernet interface to have connections for Red Pitaya and local network
* Console software (https://github.com/mri4all/console -- see instructions in Wiki)

## Other

* Silicone tube & heat exchanger for cooling system (TOOD: add model/specs)
* Two movable carts for scanner and support hardware (e.g., https://www.amazon.com/Rubbermaid-Commercial-Products-Manufacturing-FG452500BLA/dp/B006O0PMTY/)



