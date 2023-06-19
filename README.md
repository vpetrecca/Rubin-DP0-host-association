# Rubin LSST DP0 host association

This repository contains a notebook for transients to host galaxy association using the Directional Light Radius (DLR; Gupta et al. 2016).
The code was tested on the Rubin Science Platform (RSP) using DP0.2 data

Overview of the code:
- Query for host candidates in a 30'' region;
- Filter the result with user-defined cuts (depending on the transient);
- Measure the DLR for all candidates;
- Rank host candidates and identify the best host (minimum DLR);
- Produce cutouts with all the ranked candidates.
