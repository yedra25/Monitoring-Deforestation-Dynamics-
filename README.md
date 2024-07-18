# Monitoring-Deforestation-Dynamics-

## Introduction
The project focuses on the Amazon Rainforest in the Northwestern part of Brazil which has experienced a significant decline in the number of trees due to various external factors. The primary objective is to analyze and understand the core reasons of the causes, directing them to the concerned authorities for further actions and preventing deforestation in these areas.

## Research Objectives
The aim is to be able to monitor the deforestation rates in the Amazon Rainforest by using remote sensing methods and gain insights into the impacts over time. Furthermore, the collected information about the spatial and temporal changes will help in making informed decisions regarding government policies and environmental management. 

## Methodology
- Data Source: Remote Sensing data from EarthExplorer
- Study Site: Rondonia, Brazil(Latitude: 11.5057° S, Longitude: 63.5806° W)
- Temporal Extent: Every three years from 2005 to 2020.
- Data Processing: Pixel-based supervised classification using ArcGIS Pro's Image     
                   Classification Wizard and Support Vector Machine for land cover 
                   classification.
- NDVI Calculation: Python script for automating NDVI calculation and masking the   
                    deforested areas only to the images.

## Result
- Forest Area Decrease: The total forest area from 2005 to 2020, derived from 
                        supervised classification classes.
- Rate of Deforestation: Initial 5% in 2005, with significant spikes reaching nearly                            15% between 2014 and 2020.
- NDVI Analysis: Decline in healthy vegetation from 2005 to 2020.
- Change Map of Forest: Visual representation of the forest gain from 2005 to 2020.

## Discussion: 
During the analysis of the overall project, it could be inferred that the significant loss of forest in the area is due to certain factors including agriculture, logging, and infrastructure. Moreover, through the project, it can be very easily understood how crucial it is to change strategies and policies toward the environment and to promote sustainable land use practices.



