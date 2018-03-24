# [Nixie Tube Power Supply](https://wp.me/p85ddV-B1 )

See [www.surfncircuits.com](https://wp.me/p85ddV-B1)  for a complete description.  This github repository contains the Kicad Schematic, Spice Simulation, Efficiency Calculations of the 5v to 170v DCM Boost Converter for Powering your Nixie Tubes.   

![PNG of the Schematic](https://github.com/drkmsmithjr/NixiePowerSupply/blob/master/KC_NixieSupply5vTo160v/nixiesupply5vto160vdcmboost-sch.png)

__KC_NixieSupply5vto160v__:  Kicad schematic, PCB layout, BOM.  The footprint is 1.5" x 1.5" and was described and optimized in Part 2 of the blog.     The Board can be ordered from __oshpark.com__.<a href="https://oshpark.com/shared_projects/FZ5eYIVY"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>

__KC_NixieSupply5vto170vMini__:  KiCad schematic, PCB Layout, BOM of the "mini" version of the supply.   This has a footprint of 1.5" x 1" by using smaller output capacitors and using the KiCad power tools to shrink the layout.  This is the system defined by part 3 of the blog.    The layout has all the same constraints as in Part 2.  It still has four mounting holes, a USB input connector and a Terminal output connector.  The Board can be ordered from __oshpark.com__.<a href="https://oshpark.com/shared_projects/UnjheFwg"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>

__SimCalcFiles__:  Spice simulation files and DCM Efficiency Calculations.  NOTE: The LTSPICE (TM) simulation has trouble finding an initial operating point.   To get the simulation to start, use the ESC key and press it twice to skip the initial operating point.   This allows the simulation to continue and will provide a good transient response.    

__Datasheeets__: Datasheets for different inductors and the power fet.  In the Kicad Schematic, the part numbers and Digikey (TM) links are listed already.   Also the complete BOM is located in the KICAD Directory.      

See the complete blogs entry at  www.surfncircuits.com
  * [Designing a Small Footprint, Low Profile 5v to 170v Nixie Tube Power Supply (Part 1)](https://wp.me/p85ddV-A8 )
  * [Optimizing the design of the 5v to 170v Nixie Tube Power Supply (Part 2)](https://wp.me/p85ddV-B1 )
  * [KiCad Power Tools Help Shrink The Nixie Tube Power Supply (part 3)](https://wp.me/p85ddv-B1)  


