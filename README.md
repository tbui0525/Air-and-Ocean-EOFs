# Air-and-Ocean-EOFs

The following files will reproduce the figures and results from Calculation, Visualization, and Interpretation of 3D Air-Ocean Coupled Empirically Orthogonal Functions

Below is a description of each of the following folders and their contents:

- 3D Figures: This folder contains multiple downloadable HTML files that visualize the following in 3D:
  - Jan 3D Climatology : The arithmetic temperature mean for each data point over time.
  - Jan Standard Deviation: The standard deviation for each data point over time
  - Jan 3D EOF1: The first mode of the air-ocean coupled general model visualized in 3D
  - Jan 3D EOF2: The second mode of the air-ocean coupled general model visualized in 3D
  - Jan 3D EOF1 (Air Only): The first mode of the air-only model (20CRV3) visualized in 3D
  - Jan 3D EOF2 (Air Only): The second mode of the air-only model (20CRV3) visualized in 3D
 The HTML files are interactive, allowing the user to zoom, pan, and rotate the figure to have a fuller view of the data.
- Air-Ocean Coupled Model Figures: All the figures from the paper will be find here
- animation: an additional folder that includes a GIF that cannot be shown in the paper. The following images are layers of an EOF and the GIF is creating by playing the following layers in sequence.
- data: This file has a link to a Dropbox folder which contains the following data used in the computations and visualizations. Download the following files and place them into a folder named data for computations


The following files below are code to compute the figures and results seen in the paper as well as a GIF that could not be shown in the paper.
- Air No Ocean EOF Computations.ipynb : computes the EOFs for the 20CRV3 only model 
- Air and Ocean EOF Computations.ipynb : computes the EOFs for the air-ocean coupled general model
- GIF Making: Code used to create the GIF seen in the animation folder. 
