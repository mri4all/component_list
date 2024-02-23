# Component List for MRI4ALL Zeugmatron Z1

> [!IMPORTANT]
> The list of components is still being updated and incomplete. We will also try to add supplier information.

## Housing and Ringformer

* 3D-printed parts from provided STL model (TODO: Add link to 3D model)
* Requires high accuracy 3D printer (e.g., Statasys F370)

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/cac7e881-dc4a-4fe2-9eb4-8a4c13933e37" width="400"/>
  <img src="https://github.com/mri4all/components_list/assets/35747793/9f6bdfad-6c19-41ab-80f4-558fb001209d" width="400"/>  
</p>

> [!NOTE]
> Costs for 3D-printing of all needed parts are signficiant (~ $8k)


## Magnet

* 1000x N40UH magnets, 12.7 x 12.7 x 12.7 mm (TODO: add supplier)
* 300x N40UH magnets for passive shim, 3mm (TODO: add supplier)
* Plastic screws to combine magnet rings (TODO: add screw types)
  
<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/996bb5ee-00f0-4bbd-896e-b73a58938859" width="400"/>
  <img src="https://github.com/mri4all/components_list/assets/35747793/95addc5c-602d-4bbb-af80-e593bd52f85f" width="400"/>
</p>
<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/88e19d85-9305-4a5a-8d92-bb1649c18696" width="400"/>
  <img src="https://github.com/mri4all/components_list/assets/35747793/feb0cdd1-13a2-406c-8e93-3770ce2cb8c4" width="400"/>
</p>
<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/3d3e63a5-d377-44fc-967c-217351c069c9" width="400"/>
  <img src="https://github.com/mri4all/components_list/assets/35747793/9a9abea3-703d-49f6-8a6e-7233aa9375e8" width="400"/>
</p>

## Field Mapper

* 3D CNC rail set up (3x 30 cm linear CNC stages attached perpendicularly, brand: FUYU, source: Amazon)
* Arduino UNO Rev3 (https://store.arduino.cc/usa/arduino-uno-rev3)
* Arduino gShield (https://synthetos.com/project/grblshield)
* Hall probe (Metrolab THM1176 used here, USB connection, https://www.metrolab.com/products/thm1176-three-axis-hall-magnetometer/)
* Rod for connecting Hall probe to guide
* Control computer (Ubuntu 20.04 / Windows 10 or 11)
* Field mapping software (https://github.com/mri4all/field_mapper_3DFM)

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/84726ad8-7dd0-42ff-8bb5-e409d6d0466c" width="400"/>
  <img src="https://github.com/mri4all/components_list/assets/35747793/854430f9-f303-45c6-9066-cc83c0732486" width="400"/>
</p>

## Gradients

* 3D-printed wire holders with imprints
* Enameled copper wire for gradients (TODO: add specs)
* Superglue, epoxy, Kapton tape
* Gradient Power Amplifier GPA-FHDO (https://github.com/menkueclab/GPA-FHDO)
* DAC-Hat for Red Pitaya board (TODO: add source)
* Powersupply for GPA, needs DC 15V and 40A (e.g. Rohde & Schwarz HMP4040 (~ 3k) or TekPower TP1560E DC for ~ $400)
* DC feedthrough capacitor for filtering gradient waveforms (6 x Schaffner FN7563-63-M6, https://www.mouser.com/ProductDetail/Schaffner/FN7563-63-M6?qs=m2s1G0dHrOR4GHqM%252B%252BtiCA%3D%3D)
* Holder for filter capacitors (e.g., fabricated from aluminium plate)
* Depending on local power quality: Power conditioner (e.g., Furman Elite-15i)

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/09b2ef33-f45e-484e-b411-ba685eaf09b8" width="400"/>
</p>
<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/28d073ed-d90e-4a1e-b7e4-4da90f7ea7c7" width="600"/>
</p>
  
## RF Hardware

* Wire and components for RF coil (TODO: add specs)
* RF preamp (TODO: add model)
* Power supply for RF preamp DC, 15V 2A (e.g., Agilent E3610A)
* RF power amplifier (TODO: add model currently used)

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/64d00181-425c-4ddb-a569-3298ee33636d" width="400"/>
</p>


## Scanner Control

* Red Pitaya SDRLab 122-16 (https://redpitaya.com/product/sdrlab-122-16-standard-kit/)
* Computer with Ubuntu Linux 22.04 LTS (e.g., Dell Optiplex 7010 Micro)
* Additional USB ethernet interface to have connections for Red Pitaya and local network
* Console software (https://github.com/mri4all/console -- see instructions in Wiki)

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/5d7eab24-2707-45c4-a8e1-11afe97e9c74" width="400"/>
</p>

## Other

* Silicone tube & heat exchanger for cooling system (TOOD: add model/specs)
* Two movable carts for scanner and support hardware (e.g., https://www.amazon.com/Rubbermaid-Commercial-Products-Manufacturing-FG452500BLA/dp/B006O0PMTY/)

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/e63d1921-82c6-438d-a4ed-20d046895960" width="500"/>
</p>
<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/e8a538ec-3b5b-4282-b6aa-6df5ecbd8878" width="600"/>
</p>

## Optional: Active Shim with RF Shield

The active shim coil has been built during the hackathon, but has not yet been integrated into the scanner yet.

* 30 active shim coils, mounted on plexiglas cylinder
* RF shield glued to inside of plexiglas cylinder
* Controllable 30-channel amplifier for adjusting shim currents

<p align="left">
  <img src="https://github.com/mri4all/components_list/assets/35747793/e1df3931-0424-451f-8785-89b94413dc9e" width="400"/>
  <img src="https://github.com/mri4all/components_list/assets/35747793/2efb8808-cb43-49b8-9f9c-94cb8c91d765" width="400"/>
</p>

