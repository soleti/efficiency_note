## Abstract
This analysis note describes the work done to study the reconstruction efficiencies using a dataset of cosmic rays passing through the Muon Counter System (MuCS). 
The goal is to provide data and Monte Carlo reconstruction efficiencies that can be used to compare reconstruction performances and to show that an external cosmic-ray counter can be used to measure the data reconstruction efficiency in the LArTPC.

We measured the data reconstruction efficiency comparing the number of events triggered by the MuCS and the number of events with a MuCS-compatible reconstructed track. 
The Monte Carlo reconstruction efficiency, instead, was measured by comparing the number of generated cosmic rays with the number of reconstructed tracks. 

The reconstruction efficiency expressed as a function of the cosmic-ray starting angle (given by the spherical angles _theta_ and _phi_ and of the length _L_ of its path in the TPC.

Using the `pandoraCosmic` algorithm provided by the Pandora framework, the overall reconstruction efficiency is 96.1 +- 0.1 (stat) +- 1.1 (sys) for data and 96.3+-0.1 for Monte Carlo.

In the future, the method described in this paper will be adapted to use the data coming form the Cosmic Ray Tagger, which is able to tag around 80% of the cosmic rays hitting MicroBooNE LArTPC. In this way, we will cover the entire _theta_, _phi_, _L_ parameter space and measure efficiency-corrected quantities, such as the cosmic-ray flux in the LArTPC.
