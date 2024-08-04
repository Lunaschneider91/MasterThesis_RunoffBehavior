# MasterThesis_RunoffBehavior

## Introduction
This repository contains the datasets and code used for my Master's thesis on the runoff behavior in 121 catchments in Rheinland-Pfalz, Germany. 

This thesis investigates the hydrological behavior of catchments in Rhineland-Palatinate, Germany, focusing on how geology, soils, land use, and elevation influence runoff patterns. By utilizing the Delayed-Flow Index and data-driven cluster analysis, the study not only categorizes catchments but also examines the extent to which these clusters are shaped by specific landscape characteristics. This work enhances the understanding of how environmental factors shape hydrological responses through data-driven approaches, and it demonstrates new methodological perspectives for studying catchment behavior in the context of a changing climate.

## Data
The required data can be found in Seafile at the following link:
[Seafile Link](https://seafile.rlp.net/d/c4500c173e754793bec8/)

To make it easier to navigate and find the relevant information, here is a brief guide:

In the "Daten" folder, you will find several subfolders containing the corresponding files:

1_daten: This folder contains various subfolders with the relevant data.

1_abfluss: This contains the raw data, which is sorted by measurement stations.

2_dfi: Here you will find the results of the DFI. This includes DFIs for cluster analysis (1), for seasonal analysis (2), and for long-term analysis by decades (3).

3_clusteranalysis: This folder contains the results of the cluster analysis related to the data in "1_dfi".

4_geodaten: Here you will find the geodata used for calculating distributions and their comparisons (G3, G4, and G5). This folder also contains shapefiles for natural areas, a mask of Rhineland-Palatinate (based on the catchment areas), as well as the catchment areas themselves. The original file was provided by Prof. Dr. Schütz.

5_arbeitordner: This folder contains various Excel files created as intermediate steps during the work.

## Notebooks
The notebooks available here are designed for data processing, analysis, and plot creation.

1_data_preprocessing.ipynb: This notebook handles data cleaning and preprocessing.
2_distributions_statistics_plots_catchment_characteristics.ipynb: This notebook generates statistical distributions and plots related to catchment characteristics.
3_PCA_RDA.ipynb: This notebook performs Principal Component Analysis (PCA) and Redundancy Analysis (RDA).
4_seasonality.ipynb: This notebook focuses on analyzing seasonal patterns and trends.
5_long_term_changes.ipynb: This notebook examines long-term changes over time.


## Acknowledgements
Special thanks to my advisors, Mr. Schütz and Mr. Casper, for their guidance and support.
I also extend my gratitude to my family, friends, and my partner Christoph Rieff for their encouragement and assistance.
