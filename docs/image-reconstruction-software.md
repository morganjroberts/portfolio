# Medical Image Reconstruction Software

## Problem
During ultrasound tomography, data is collected by transmitting ultrasound pulses into the object. The ultrasound waves interact with the object, producing a scattered field, which is measured by an array of transducer elements.

The goal of ultrasound tomography is to visualise the internal features of the object. For example, in breast cancer imaging we want to see inside the breast tissue to identify suspicious lesions and classify then as malignant or benign. Image reconstruction algorithms transform the raw measured ultrasound data into images.



## Solution - Data Processing Pipeline

I developed a Matlab GUI to provide a simple pipeline for data acquisition, calibration, data pre-processing and image reconstruction for the open-source ultrasound tomography system: [open-UST](./open-source-ultrasound.md). 

The GUI uses object oriented 

## Impact
- Packaging the reconstruction code into a GUI has made open-UST a turnkey system. This has made ultrasound imaging more accessible to people with no background in software or ultrasound.
- Acquisition, calibration and processing settings are saved automatically, improving data management.


During my PhD I developed 

serial comms
file management
calibration
object oriented and functions
efficient code (vectorisation) for speed
