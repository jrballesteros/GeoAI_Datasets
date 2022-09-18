# GeoAI_Datasets
Contains scripts of the methods described in the paper "A GIS pipeline to produce GeoAI Datasets from Drone Imagery"

1. To download vector ground truth layers from OSM world database using the specific Overpass API library (https://pypi.org/project/overpass/ (accessed on 2 march 2022)).

2. Scripts for the methods are in the file: GIS_Pipeline_Methods.ipynb
- Crop orthomosaics in areas for test and training datasets
- Geometric and Spectral Augmentation (optional)
- Tessellation
- Imbalance checking and remove of extremely imbalance img,msk (<1%) (optional)
- Pairing img,msk into sole images (optional)
- Dataset random splitting into train and validation.

3. An ArcGIS Model Builder model to create masks based on buffer size (GIS Pipeline.tbx)

4. Links to example of datasets produced by the pipeline are in Appendix A of the paper.
