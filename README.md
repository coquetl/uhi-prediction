# NYC Urban Heat Island Prediction

## 1)	What is this project about ?
The Urban Heat Island (UHI) effect is an issue resulting in temperature variations between rural and urban environments that exceed 10-degrees Celsius in some cases, and can cause significant health-, social-, and energy-related issues. Urban areas are most susceptible to heat stress due to the high density of buildings, lack of vegetation (green space), lack of water bodies, and waste heat from industry and transportation. <br />
To measure this effect, we use an UHI Index = (Temperature at a given location) / (Mean temperature for all locations). <br />
The goal of this project is to develop a digital model to predict the locations and severity of the UHI effect and to understand the drivers of this phenomenon, in New York City (Manhattan and The Bronx).

This work was done under the *2025 EY Open Science AI&Data Challenge Program*, with over 10,000 participants from 115 countries.
With a final score of 95.96%, I was ranked 93/380 among external participants.

## 2)	How to go into the project ?
- *0_Urban heat island.pdf* is a detailed pdf report about the methodology and results of the project
- *1_Data_extraction_Landsat_LST.ipynb* is a code to exctract Landsat data
- *2_Data_extraction_Sentinel2_GeoTIFF.ipynbf* is a code to exctract Sentinel 2 data
- *3_UHI_Prediction.ipynb* is the main code to run the project

## 3)	Concepts
- Manipulation of geospatial and satellite data
- Multi-spectral and multi-distance analysis
- Pre-processing : Focal buffers, indices, standard scaler
- Random Forest Regressor, features importance
- Cross validation method amd R2 metric

## 5)	CONCLUSION
Emerging tools, like satellite and climate data are now essential tools to analyze, monitor and assess our human impact over large areas. They are helping to evaluate the risks and develop appropriate strategies and solutions against hazards and vulnerabilities. <br />
In this used case, we saw that lower-density urban areas are often cooler than high-density, and that vegetated/watered areas are cooler than urbanized areas. Also, more than identifying the causes, the model can predict the localization of the UHI and their scale, which can be useful for the city in case of heatwave.




