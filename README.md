# "Monitoring Cropland Phenology on Google Earth Engine Using Gaussian Process Regression" demo codes.
\
\
Guidelines and demo codes from the publication
\
https://doi.org/10.3390/rs14010146
\
![image](https://user-images.githubusercontent.com/9076763/169662944-b7b6f85d-8251-4839-9d97-0b65d3e882fa.png)
\
To add the GEE repository containing the scripts to your GEE accounte click below:
\
https://code.earthengine.google.com/?accept_repo=users/msalinero85/GPRPhenologyDemos
\
![image](https://user-images.githubusercontent.com/9076763/169662967-9ba86550-69c0-4d8a-909a-de15d981f081.png)

The repository includes the following running demos:
1. **GPRPredictedMean:** GPR predicted mean map generation for the entire S2 30TUM tile along with its RGB image.
\ 
![image](https://user-images.githubusercontent.com/9076763/169663066-330fc7f6-e655-4a2b-80b5-fbb51267581f.png)
\
3. **GPRGapfilling:** GPR gap-filling map generation for the entire S2 30TUM tile.
\
![image](https://user-images.githubusercontent.com/9076763/169663089-a90f7b97-6d73-485e-b3ab-ccfc565bb394.png)
\
5. **LSPGeneration:** LSP metrics generation for the 30TUM tile with its visualization.
\
![image](https://user-images.githubusercontent.com/9076763/169663157-a91183a4-6cb2-4014-baa9-317cc11b46a5.png)


Other important scripts contained in the repo:

4. **S2BOAModels:** GPR models hyperparameters translated from ARTMO(matlab) to GEE.
\
6. **PhenologyFunctions:** Double Logistic implementation and auxiliary functions to retrieve the LSP metrics.
\
8. **visualization:** Parameters required for visualization (palettes, min, max...) 
\
