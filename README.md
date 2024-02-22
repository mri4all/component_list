# Components List for MRI4ALL Zeugmatron Z1

> [!IMPORTANT]
> The list of components is still being updated and incomplete. We will also try to add supplier information.

## Housing

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
* Hall probe (Metrolab THM1176 used here, USB connection)
* Rod for connecting Hall probe to guide
* Control computer (Ubuntu 20.04 / Windows 10 or 11)
* Field mapping software (https://github.com/mri4all/field_mapper_3DFM)

## Gradients

## RF Hardware

## Scanner Control

* Red Pitaya SDRLab 122-16 (https://redpitaya.com/product/sdrlab-122-16-standard-kit/)
* Computer with Ubuntu Linux 22.04 LTS (e.g., Dell Optiplex 7010 Micro)
* Additional USB ethernet interface to have connections for Red Pitaya and local network
* Console software (https://github.com/mri4all/console -- see instructions in Wiki)

## Other


