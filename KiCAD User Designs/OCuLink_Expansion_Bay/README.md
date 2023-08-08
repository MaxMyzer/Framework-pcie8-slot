 # Dual OCuLink 4i + DisplayPort Expansion Card 

This is for attaching external PCIe Gen 4 x8 Devices via dual OCuLink 4i connectors.
For use with GPUs, the DisplayPort Input is exposed - this is NOT for Display Output!

<image src="production/Image_Wide.png">

## Order Guide

<image src="production/Image_Wide_Order.png">

<i>It is not recommended to order yet as the Expansion Card specification are not yet finalised/clear</i>

This board has been designed with jlcpcb's JLC04121H-3313 stackup - that means the trace widths and spacing are chosen for a PCB with the same parameters. Buying elsewhere might need adjustments.

There are two versions of the board since jlcpcb adds around 14€ if your board is larger than 100mm - but be aware the 100mm wide board does not have sufficient screw holes at the back of the board, so with bigger connectors, this will pose a problem.

For either board, after uploading the respective production**.zip files to https://cart.jlcpcb.com/quote, you do the following:
1. Select 4 Layers
2. Set PCB Thickness to 1.2mm
3. Set Material Type to FR4 TG155 (for better hole tolerances)
4. Set Surface Finish to ENIG (for much better surface, important for interface connector)
5. Select Yes for Impedance Control, and select "JLC04121H-3313" in the popup (or later)

Then, for the stencil (which you require to put down solder paste for the reflow):
1. Enable Stencil ordering together with the PCB
2. Select Yes for Customised Size, select the Custom Size option, and enter 140/120mm (depending on the version) x 100mm. If you don't do this, you pay for a 1kg metal plate to be shipped to you
3. Set Stencil Side to Top
4. Set Polishing Process to Etching (since we have tiny 0.5mm pads)

Expected price weight: <br>
100mm version: 34€ + 0.42kg shipping <br>
Wide 120mm version: 49€ + 0.44kg shipping <br>