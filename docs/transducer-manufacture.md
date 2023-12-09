# Transducer Manufacture

During my PhD I manufactured a 256-element transducer ring array for ultrasound tomography from scratch. Prior to this work, an instructional guide for in-house transducer manufacture did not exist.

Five rounds of prototyping were completed to develop a manufacturing framework (**[morganjroberts.github.io/open-UST](https://morganjroberts.github.io/open-UST/)**) that satisfies these key constraints:

- Low variation in acoustic behaviour
- Low cost
- Make use of widely accessible manufacture equipment e.g. rapid prototyping.

There were many design and manufacturing challenges, here are some examples:

## Problem 1 - Piezoelectric crystal alignment

It is important to know the exact position and orientation of the individual transducer elements within a single transducer module. This allows accurate prediction of how ultrasound waves travel between them, during image reconstruction. This leads to higher quality medical images with less artefacts.

### Solution

I developed a method to register 16 piezoceramic elements using a 3D-printed polyvinyl alcohol (PVA) mould. The slot geometry was highly optimised for filament deposition printing, using drafted under-cuts and corner reliefs to allow the elements to fit tightly in the slots with no play.

While the piezoceramic elements are held in this mould, a composite "backing layer" is cast behind them. After this cures, the PVA mould dissolves in water, leaving the piezoceramic elements bonded to the composite in the correct position.

This method was very successful: for a large batch of 256 elements, the lateral skew (1.2$^{\circ}$ ) and axial position (104 $\mu$m ) errors were comparable to commercial systems manufactured using advanced equipment.

## Problem 2 - Matching layer deposition

A thin layer of composite (~165 $\mu$m) is usually deposited onto piezoceramic elements to improve their transmit output and receive sensitivity. The layer must be uniform and must bond very well to the piezoceramic elements electrode.

### Solution

To address delamination defects, I developed a careful cleaning electrode procedure using abrasives and solvents - this improved yields from 45% to 94% during prototyping.

Methods already existed used to deposit thicker 600 $\mu$m layers on large piezoceramic elements with rapid prototyping technology. However, after testing these were determined to be unsuitable for thin layers on small crystals, due to their high interbatch variation in thickness ($\pm$50 $\mu$m).

Instead, through several rounds of prototyping I developed a novel matching layer deposition method. The composite layer was blade coated and then compressed onto the piezoceramic element using a glass plate, adjusting the compression depth using inexpensive precision gauge blocks as a positive stop.

This resulted in a total standard deviation of $\pm$13.6 $\mu$m across 256 transducer elements. See [Further Reading](publications.md) for more technical information!

## Impact

By optimizing each aspect of the transducer manufacture process, the final 256-element transducer ring array achieved performance levels comparable to those of commercial systems made with sophisticated equipment.