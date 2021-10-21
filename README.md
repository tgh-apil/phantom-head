# Phantom Head

This phantom head was created for use in NIOSH-compliant respiratory mask testing. 

## Development
We used publically available [ISO digital headforms](https://www.cdc.gov/niosh/npptl/topics/respirators/headforms/default.html) (specifically the medium size)—which were developed from anthropomteric data collected by NIOSH—as our base. The head itself was printed at 90% scale, with the remaining 10% filled with silicone to simulate a layer of human flesh and to provide a seal for each mask tested. The head went through four design iterations, as detailed below, before reaching the final design used in testing. Meshmixer was used for the entire process.

### V1
[pictures]

The initial version of the head included a tube that ran from the mouth out through the back of the head, exiting into a hollowed out portion that would provide users with the necessary room to adjust respiratory tubing. The front part of the tube was only 2mm thick, and extended out quite far (in line with the tip of the nose), which was likely to be too flimsy once actually printed.

### V2
[pictures]

The following changes were made to V1:
* The thickness of the front tube was increased from 2mm to 3.5mm to ensure it would print without snapping during the removal of supports or insertion of tubing.
* The front tube was also shortened slightly to better fit into masks. Where V1 had the tube aligned with the tip of the nose, V2 goes approximately halfway.
* The hole in the back was made diamond-shaped to reduce the need for supports in that area when printing.
* The compexity of the back tube was reduced.

This version of the head was printed at 40% scale, along with a negative mold at 50% scale to test the silicone mold-making process. (Note: this mold was not printed with a hole to pour silicone through; that was drilled into the mold once it was printed.)
[pictures of post-mold head]

### V3
[pictures]

The following changes were made to V2:
* The head was scaled to 90%, while the tubing inside the head was designed at 100% scale, so the entire head file could be printed as-is, while allowing the head to fit its mold with a 10% gap for silicone and to maintain proper tube sizing.
* Both the front and back tubes were given an inner diameter of 25mm, with a 2mm thickness (i.e. one continuous tube).
* The front tube was brought forward by roughly 1cm to make it easier to cut away any excess silicone after molding, allowing tubing to be attached to the front of the head. (Note that in our V2 silicone mold test, the silicone has completely covered the front tube in the mouth area.)
* A diamond shaped plud was also printed to place in the hole in the back to help prevent silicone from seeping in during the pouring process.
* A hole for pouring the silicone in through was made in the mold prior to printing. As the mold was quite a large one, it was printed in 8 separate pieces to accomodate the printers' size limitations.

### V4
[pictures]

The following changes were made to V3:
* The continuous tube's thickness was increased to 3mm (while still maintaining a 25mm internal diameter) and a volume of 40mL based on NIOSH CO2 testing requirements. 
