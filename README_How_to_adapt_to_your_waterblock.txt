README — How to Adapt This Mount to Your Waterblock
=================================================

This 3D-printable mount was designed for the cable-free (non-Wired), Normal-orientation Thermal Grizzly WireView Pro II. It allows the WireView to be mounted beside a vertically installed graphics card fitted with a GPU waterblock.

The original mount was designed and physically tested with the Alphacool Core GeForce RTX 5090 waterblock for MSI Suprim X / Vanguard (Alphacool article 10268).


ADAPTING THE MOUNT TO ANOTHER WATERBLOCK

The design may also be adapted to other GPU waterblocks, including those made by other manufacturers, provided they have a similar construction: a front acrylic (plexiglass) section, a rear backplate, suitable mounting spacers, and sufficient free space between the relevant parts.

Three dimensions are specific to my Alphacool waterblock:

1. Vertical mounting bar height: 132.24 mm.
2. Center-to-center distance between the geometric centers of the upper and lower hooks: 123.00 mm.
3. Distance from the FRONT face of the vertical mounting bar to the FRONT face of the rear retaining tab: 21.00 mm.

The rear retaining tab is designed to extend BEHIND the GPU waterblock's backplate, helping prevent the mount from tipping. The 21.00 mm dimension is measured between the two FRONT faces described above, not from the rear of the bar. It's the distance between the back of the acrylic plate and the back of the backplate.


VARIABLE BAR THICKNESS — PCB COMPONENT CLEARANCE

The vertical mounting bar is deliberately NOT the same thickness along its entire height. On the original design, its front face remains flat and continuous, while the bar is thinner toward the bottom on the rear side: 8.0 mm in the lower section and 12.0 mm in the upper section, with a smooth transition between 60.0 and 65.0 mm above the bottom. This shape provides clearance for electronic components soldered near the edge of the GPU PCB.

When adapting the model to a different waterblock or graphics card, inspect the PCB edge and the position and height of nearby soldered components. You may need to modify the bar thickness profile and its transition, in addition to the three main dimensions listed above. Maintain a safe clearance: the support must never press against the PCB or any electronic component.

To adapt the mount, measure the corresponding three dimensions on your own waterblock, then load the supplied STEP 3D model into an AI-assisted CAD workflow and ask it to modify these dimensions to match your measurements. Check the hook diameter and spacer locations, backplate clearance, PCB/component clearance, and WireView fit as well. Inspect the modified model and test-fit it before relying on it.


OPEN OR CLOSED HOOKS

On my version, the two hooks are OPEN. This makes it possible to install the mount on an already assembled graphics card and waterblock without disassembling the GPU.

If your graphics card has not yet been assembled into its waterblock, you can instead ask the CAD tool to replace the open hooks with CLOSED circular loops (complete rings with central holes). These can be positioned around the appropriate spacers during waterblock assembly, potentially providing a more captive mounting arrangement afterward. Confirm that the ring geometry does not interfere with the waterblock assembly, fasteners, or specified tightening requirements.


ADAPTING THE MOUNT TO WIREVIEW II PRO WIRED VERSION

This mount can also be adapted to the Thermal Grizzly WireView Pro II Wired version. The main difference should be the device's thickness, so the WireView cradle would need to be made deeper to accommodate it. An internal clearance of 34 mm should theoretically work, but this dimension has not been verified and must be checked before printing


IMPORTANT

This is an independent, community-made design. Other waterblocks may require more than these three dimensional changes, particularly to the variable thickness of the vertical bar. Do not force the hooks onto spacers, compress the PCB, obstruct cooling or ventilation, or allow the mount to interfere with electrical connectors. Verify the final CAD geometry and physical clearances before installation.
