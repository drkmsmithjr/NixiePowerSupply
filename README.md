# [Nixie Tube Power Supply](https://wp.me/p85ddV-B1 )

See [www.surfncircuits.com](https://wp.me/p85ddV-B1)  for a complete description.  This github repository contains the Kicad Schematic, Spice Simulation, Efficiency Calculations of the 5v to 170v DCM Boost Converter for Powering your Nixie Tubes.   

__KC_NixieSupply5vto160v__:  Kicad schematic, PCB layout, BOM .  The Board can be ordered from __oshpark.com__. <a href="https://www.oshpark.com/shared_projects/tlxvfv5F"><img src="https://www.oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>   
  
__SimCalcFiles__:  Spice simulation files and DCM Efficiency Calculations.  NOTE: The LTSPICE (TM) simulation has trouble finding an initial operating point.   To get the simulation to start, use the ESC key and press it twice to skip the initial operating point.   This allows the simulation to continue and will provide a good transient response.    

__Datasheeets__: Datasheets for different inductors and the power fet.  In the Kicad Schematicc, the part numbers and Digikey (TM) links are listed already.   Also the complete BOM is located in the KICAD Directory.      

See the complete blogs entry at  www.surfncircuits.com
  * [Designing a Small Footprint, Low Profile 5v to 170v Nixie Tube Power Supply (Part 1)](https://wp.me/p85ddV-A8 )
  * [Optimizing the design of the 5v to 170v Nixie Tube Power Supply (Part 2)](https://wp.me/p85ddV-B1 )

__Work in Progress__ :   

__KC_NixieSupply5vto170vMini__:  I'm  working on taking the current design and shrinking it to be 1.5"x1" using smaller output capacitors but still having four mounting holes, a USB input connector and a Terminal output connector.    I would love to have some help completing this,  please send in a __Pull Request__.


