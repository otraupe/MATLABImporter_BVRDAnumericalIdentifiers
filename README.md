"# MATLABImporter_BVRDAnumericalIdentifiers" 

This project addresses sync issues of markers from the BrainVision RDA interface streamed to LSL (https://github.com/sccn/labstreaminglayer) via the BrainVisionRDA app (https://github.com/sccn/labstreaminglayer/tree/master/Apps/BrainProducts/BrainVisionRDA) - namely the fact that those markers don't get de-jittered properly and, thus, are out of sync with the EEG data.

This project part performs the post-processing by means of an updated version of LSL's Matlab Importer (https://github.com/sccn/labstreaminglayer/tree/master/Apps/MATLABImporter). It operates on a temporary marker identifier channel in the EEG data allowing for the transmission of the corresponding EEG time stamps on to the markers in question - created by the corresponding project part hosted here: https://github.com/otraupe/BrainVisionRDA_numericalIdentifiers.
