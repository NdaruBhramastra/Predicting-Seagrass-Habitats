# Seagrass Habitat Prediction Using Spatial Machine Learning

A geospatial machine learning project focused on predicting potential seagrass habitat using known seagrass occurrence data and environmental conditions across coastal waters.

The project integrates **GIS, spatial statistics, geostatistics, and machine learning** to model the relationship between seagrass presence and oceanographic conditions. I prepared training data from known seagrass habitats, generated environmental prediction surfaces using **Empirical Bayesian Kriging (EBK)**, and used environmental variables including temperature, salinity, dissolved oxygen, nitrate, phosphate, silicate, and water depth as model predictors.

The workflow included:

* Preparing and cleaning spatial datasets for analysis
* Generating random training points within known seagrass habitats
* Interpolating oceanographic measurements using **Empirical Bayesian Kriging**
* Creating continuous raster surfaces for environmental predictor variables
* Applying **Maximum Entropy (MaxEnt) presence-only modeling** to predict potential seagrass habitat
* Evaluating and refining model outputs based on prediction results and model diagnostics
* Producing spatial predictions to identify areas with greater potential for seagrass habitat

### Tools & Techniques

**ArcGIS Pro · Spatial Statistics · Geostatistics · Empirical Bayesian Kriging · MaxEnt · Raster Analysis · Spatial Machine Learning · Environmental Modeling**

### Data

The analysis uses seagrass occurrence data and oceanographic measurements representing environmental conditions associated with seagrass habitats.

This project was completed as part of an [Esri Learn ArcGIS tutorial](https://learn.arcgis.com/en/projects/predict-seagrass-habitats-with-machine-learning/), with the workflow reproduced and explored as a practical exercise in spatial machine learning and environmental modeling.
