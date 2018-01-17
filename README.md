# PCB-milling

PCB milling can be seen as printing a circuit on to a piece of copper. This allows us to
check our design before having it Professionally made.

The milling is done on a copper substrate, it is a piece of fiber glass which has one side or both side covered in copper. The copper layers are what form the traces after being put through the milling machine.

The main purpuse here is to test different end mills and settings to get a decent result in PCB milling

## CNC Router

A CNC router is a computer-controlled cutting machine related to the hand held router used for cutting various hard materials, such as wood, composites, aluminium, steel, plastics, and foams. CNC stands for computer numerical control.
Here the following CNC router is tested for the PCB milling process.

<img src="http://www.cnc-shop.ch/user/cimage/3040-03.jpg" width="350">

This CNC router is from (CNC Shop)[http://www.cnc-shop.ch/cnc3040.html]

* Model: 3040 v3.0
* Weight: 40kg
* Materiel: Casted aluminium
* Spindle speed: 6000 - 24000 tr/min
* Spindle power: 800W
* Collet fixture: ER11

Dimensions |  X  |  Y  |  Z  |
-----------|-----|-----|-----|
Travel size| 300 | 400 |  50
Table siez | 320 | 580 |  85

## Milling bits

Milling cutters are cutting tools typically used in milling machines or machining centres to perform milling operations They remove material by their movement within the machine or directly from the cutter's shape
The milling bits are fixed to the spindle by usinf ER 11 collet.
Tool Shank Diameter : 3 mm

### Trace cutout bits (Endmill)

Precision endmills are used to cut out the copper so that traces
are formed on the copper conductor.

* Solid Carbide V-Shaped Engraving Tool Bit

<img src="http://www.2linc.com/images/dim-microprofiler_1-8.jpg">

Included angle | Tip width | Price | Suplier
---------------|:----------|:------|:-----
       10°     |    0.1    | 5 bits for 6,50 € |[Amazon](https://www.amazon.fr/gp/product/B00D3GU558/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1) |
       15°     |    0.1    | 1 bit for 13,50 € |[Iron wood](http://www.ironwood-distribution.com/stylets_diametre_3/stylet_d3_angle_15%C2%B0/stylet-ve-diametre-a15-e0-10-p-3842.html) |
       45°     |    0.1    | 10 bits for 1 € |[Ebay](https://www.ebay.com/itm/1-5-10PCS-Carbure-Gravure-CNC-PCB-45-0-1mm-Fraise-Foret-Couteau-Plat-3-17MM/322578275122?ssPageName=STRK%3AMEBIDX%3AIT&var=511564367365&_trksid=p2057872.m2749.l2649) |
       10°     |    0.2    | 1 bit for 4.99 € |[Ebay](https://www.ebay.com/itm/%C3%98-3x10-X-0-2mm-type-V-Burins-de-GRAVURE-pour-cnc-machine-Graveur/391434920942?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649) |
       15°     |    0.2    | 1 bit for 13,50 € |[Iron wood](http://www.ironwood-distribution.com/stylets_diametre_3/stylet_d3_angle_15%C2%B0/stylet-ve-diametre-a15-e0-10-p-3842.html) |

* Tough Tip Engraving Tool

<img src="http://www.2linc.com/images/dim-tough-tipAL_1-8.jpg">

Flute | Included angle | Tip width | Price | Suplier
:-----|:---------------|:----------|:------|:-----
 1    |       25°      |    0.2    | 1 bit for 9,60 € |[CNC Fraises](https://www.cncfraises.fr/pointes-javelots-1-dent-evo/237-pointe-javelot-1-dent-25-degres-gravure-circuit-imprime.html) |

* Other interesting engraving tips

http://www.2linc.com/engraving_tools_tough_tip.htm
http://www.2linc.com/engraving_tools_composite.htm

### Drill bits

Used to drill holes for through hole parts and mouting holes.

* Micro drill bits

<img src="http://www.ironwood-distribution.com/UserFiles/Image/CNC_PLUS/MICROS_FORETS/Micro_forets_Schema.jpg">

D      | L1     | A     |  Price | Suplier
-------|:-------|:------|:-------|:--------
0.6 mm |7.0 mm  |  130° |3,40 €  |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-60-17-hss-p-3165.html) |
0.7 mm |10.5 mm |  130° |3,40 €  |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-70-17-hss-p-3167.html)
0.8 mm |10.5 mm |  130° |3,40 €  |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-80-17-hss-p-3169.html)
1.0 mm |10.5 mm |  130° |3,40 €  |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-17-hss-p-3173.html)
1.2 mm |10.5 mm |  130° |3,40 €  |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-20-17-hss-p-3177.html)
1.5 mm |10.5 mm |  130° |3 €     |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-50-17-hss-p-3181.html)
3.0 mm |10.5 mm |  130° |3 €     |[Iron wood](http://www.ironwood-distribution.com/outils_fraisage/micros_forets/micro-foret-00-17-hss-p-3196.html)

### Routing cut-out bit

Used to cut out pcb once milling is finished

* Titanium Coat Carbide

<img src="https://images-na.ssl-images-amazon.com/images/I/311p6lzq7rL._SX425_.jpg" width="300px">

D                |  Price | Suplier
-----------------|:-------|:-----------
0.6 mm to 1,5 mm |3,40 €  |[Amazon](https://www.amazon.fr/gp/product/B00OPY6R6I/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1) |


## Softwares

* CNC : Mach3
* Eagle CAD
* [pcb-gcode](http://pcbgcode.org/list.php?12)

## Tutorials

* [sparkfun](https://learn.sparkfun.com/tutorials/using-eagle-schematic)
* [Instructable](http://www.instructables.com/id/Make-your-own-PCBs-on-an-inexpensive-desktop-CNC-m/)

## Supplier

* [Ironwood](http://www.ironwood-distribution.com/outils_fraisage-c-20.html)
* [CNC Frainses](https://www.cncfraises.fr/)
* [2linc](http://www.2linc.com/)


## What Not To Do
* Don't drop the bits. They will break.
* Don't crash the tool. I know you're going to crash the tool because you don't know what you're doing, so remember not to crash the tool and you'll feel bad when you crash the tool and probably won't do it again. Just raise the spindle before you go crazy hitting return to zero and if you stop a program don't just restart it somewhere in the middle and expect everything to be OK.
* Don't forget to wear eye protection. The CNC machine is a robot that cuts things and it's not sophisticated enough to follow Asimov's laws about not hurling bits of metal into your eye.
* Don't start and stop the PC with the spindle turned on. That thing is just hooked up to a pin on the parallel port and that pin gets mercilessly diddled by legacy windows upnp probing which may surprise and/or hurt you by running the spindle. Just turn it off.
* Don't leave the mill running unattended. You need to be there to hit the pretty red e-stop button when something horrible happens.
* Don't leave a mess for the next person.
