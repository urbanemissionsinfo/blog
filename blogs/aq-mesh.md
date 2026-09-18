# Introducing AQ-MESH

Spatial disaggregation of emissions to a grid is a (big) challenge in building an emissions inventory. These days, finding a gross activity record and a library of emission factors is a search or a prompt away, but how to I allocate this (activity * factor) product to grids of desired resolution (e.g., 1 km for urban scale or 10 km for regional), still remains uncertain.

![alt text](blogs/aq-mesh.jpg)

As part of our concepts-building course, we use the [AQ-MESH tool](https://urbanemissions.info/tools/aq-mesh-mapping-of-emission-estimatesto-hotspots/) -- Mapping Emission Estimates to Hotspots, to understand this process.

Which proxies are useful and how to play with weights
What is the uncertainty in using 10 vs 3 proxies

The efficacy of these distributions needs to be tested through a chemical transport model to know if we need to use 10 proxies or the results okay with using 2 or 3 representative proxies, and how the allocated weights perform. More is always helpful in explaining the methods; which also means more time spent in preparing the inputs in the desired formats. 

During the class, we go through these as case studies.
Tool is available on GitHub and example files (and an excel version) are here: [AQ-MESH](https://urbanemissions.info/tools/aq-mesh-mapping-of-emission-estimatesto-hotspots/)