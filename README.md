# "Monitoring Cropland Phenology on Google Earth Engine Using Gaussian Process Regression" demo codes.
\
\
Guidelines and demo codes from the publication https://doi.org/10.3390/rs14010146

* To add the GEE repository containing the scripts to your GEE accounte click below:
https://code.earthengine.google.com/?accept_repo=users/msalinero85/GPRPhenologyDemos

The repository includes the following running demos:
1. GPRPredictedMean: GPR predicted mean map generation for the entire S2 30TUM tile along with its RGB image. 
2. GPRGapfilling: GPR gap-filling map generation for the entire S2 30TUM tile.
3. LSPGeneration: LSP metrics generation for the 30TUM tile with its visualization.

Other important scripts contained in the repo:
4. S2BOAModels: GPR models hyperparameters translated from ARTMO(matlab) to GEE.
5. PhenologyFunctions: Double Logistic implementation and auxiliary functions to retrieve the LSP metrics.
6. visualization: Parameters required for visualization (palettes, min, max...) 
