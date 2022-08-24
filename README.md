# GeoAI_Datasets
Contains scripts of the methods described in the paper "A GIS pipeline for the production of GeoAI datasets from drone imagery"

1. To download vector ground truth layers from OSM world database using the specific Overpass API library (https://pypi.org/project/overpass/ (accessed on 2 march 2022)).

2. Scripts for the methods are in the file: GIS_Pipeline_Methods.ipynb
- Spectral, Geometric Augmentation
- Tessellation
- Imbalance checking and remove of imbalance img,msk
- Pairing img,msk into sole images
- Dataset random splitting into train, validation and test datasets.

3. An ArcGIS Model Builder model to create masks based on buffer size (GIS Pipeline.tbx)

4. Links to datasets created are in Appendix A of the paper.
