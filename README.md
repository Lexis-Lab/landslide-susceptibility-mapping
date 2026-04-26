# Landslide Susceptibility Mapping
## OGS × University of Padua — PhD Mini-Project Stage 2

### Study Area
Friuli-Venezia Giulia region, northeastern Italy
Coordinates: 45.58°N–46.65°N, 12.30°E–13.95°E

### Project Overview
This project builds a landslide susceptibility map using:
- Terrain derivatives (Slope, Aspect, TWI) from Copernicus GLO-30 DEM
- Sentinel-1 InSAR LOS velocity and coherence (COMET-LiCS)
- Random Forest machine learning classifier
- Spatial block cross-validation

### Tasks
- Task 1: GIS Data Preparation
- Task 2: InSAR Processing
- Task 3: Machine Learning Model
- Task 4: Interpretation and Reflection

### Results
- AUROC: 1.0
- F1-Score: 1.0
- Key finding: Slope was the dominant predictor of landslide susceptibility

### Limitations
- Synthetic landslide mask used (IFFI inventory download issue)
- InSAR alignment could not be completed due to CRS mismatch
- Model overfitting due to label-feature correlation

### Data Sources
- DEM: Copernicus GLO-30 via OpenTopography
- InSAR: COMET-LiCS Portal (Frame 044A_04329_131313)
- Landslide Inventory: IFFI via IdroGEO (ISPRA)
- Sentinel-2: Google Earth Engine

### How to Run
1. Open each notebook in Google Colab
2. Mount your Google Drive
3. Run cells in order from Task 1 to Task 4

### Requirements
See requirements.txt for all Python dependencies

### Author
OGS × University of Padua PhD Application
Supervisor: Dr. Sansar Raj Meena | smeena@ogs.it
