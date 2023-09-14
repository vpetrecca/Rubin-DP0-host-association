# Rubin LSST DP0 host association

This repository contains a notebook for transients to host-galaxy association using the Directional Light Radius (DLR; Gupta et al. 2016).

The code was tested on the Rubin Science Platform (RSP) using DP0.2 data.

If you have access to the RSP (e.g., you are a Rubin DP0 Delegate), you can clone this repository into your own directory and run the tutorial notebook. 

An example .csv file with transient coordinates to run the code is also provided. 

---------------------------------------------------------------------------------------------------------------------------

Overview of the code:
- Query for host candidates in a 30'' region;
- Filter the result with user-defined cuts (depending on the transient);
- Measure the DLR for all candidates;
- Rank host candidates and identify the best host (minimum DLR);
- Produce cutouts with all the ranked candidates.

---------------------------------------------------------------------------------------------------------------------------

Contact the author for any issues: vincenzo.petrecca@inaf.it
