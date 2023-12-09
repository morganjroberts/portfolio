# Materials Characterisation Equipment

## Problem

When focusing ultrasound waves into the brain during neuromodulation, energy is absorbed by the hair, skin, and skull. To predict correct intensity dosages in the brain, you need to know the acoustic absorption of these different materials.

I was tasked with building a dedicated experimental setup to accurately measure the acoustic properties of materials using a "sample insertion method".

## Specification

For the sample insertion method, the sample is immersed in a water bath. A transmitter sends an ultrasound wave through the sample, which is detected at the receiver. Then, the measurement is repeated with the sample removed (water only). The acoustic properties of the sample can be estimated based on the differences between the two measurements.

There were key alignment requirements:

- The transmitter and receiver beam axes must be exactly aligned (maximum $\pm$0.5 mm colinearity error over 500 mm).
- The sample must be exactly perpendicular to the beam axis (maximum 0.5$^{\circ}$ error).
- Removing and replacing the sample must not disturb the experiment.
- The receiver and sample positions along the transmitter beam axis must be adjustable.

There were other requirements:

- Materials must be immersible in deionised water for long periods.
- Maximum lead time 3 weeks - this made outsourcing not an option.

## Solution

I built the tank from 12 mm cast acrylic sheets using solvent welding, with acrylic-filled dichloromethane adhesive. The edges were trimmed with a router and polished.

To adjust the receive and sample positions axially, linear rails were installed above the tank with linear bearings supporting two carriages. A receiver mount and sample frame were suspended from the carriages, which have locking handles to secure the receiver and sample during measurement.

The transmitter beam axis was aligned with the receiver using a laser pointer.

The receiver position can be finely adjusted in X and Y using fine pitch machine screws. Since these adjustments are expected to be small and infrequent, this simple approach is more suitable than using a 2-axis translation stage with sliding ways and lead screws.

A sample mount was designed to provide a generic hole layout for a range of different sample geometries. A wedged feature on the mount is pulled tightly against a pin on either side of the frame. This means that the sample mount always returns to the same position.

## Impact

- From design to delivery took only 3 weeks since I manufactured everything on an in-house milling machine. THis enabled important measurements to take place on schedule. 
- The tank increased our in-house acoustic measurement capability - previously we have had to outsource these measurements to guarantee accuracy (which has a longer lead time and higher cost).
- The system met all the alignment criteria, with a colinearity error of only $\pm$0.5 mm over 500 mm.
