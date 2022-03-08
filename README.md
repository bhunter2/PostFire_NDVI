# Postfire_NDVI
Git Hub Repository for the final project for GEOG 590. 
Team members: Brooke Hunter and Jon Sheppard
University of Oregon Department of Earth Sciences and Geography

**Project Title**: Vegetation analysis of fire affected region in the context of land management

**Summary**: To look at the initial impact of and subsequent vegetation recovery after disturbance, we will use a time series of Landsat imagery prior to and after three fires in southwest Oregon. We will use NDVI as a proxy for vegetation health and coverage to complete a change detection analysis of vegetation. Furthermore, we will split our data into privately and publically managed lands to see the role land managment has on vegetation recovery.

**Need to update**
Wildfire frequency and intensity has increased in recent years. In Oregon, a checkerboard of privately and publicly owned land has resulted in a landscape that has sharp boundaries between clear cut and vegetated regions. How doe this pattern affect the long-term recovery of vegetation? In our project we aim to investigate how this pattern of private and public land management influences vegetation recovery through normalized differenced vegetation index analysis (NDVI) over time pre and post-fire.

**Questions**
-	How quickly does vegetation recover after wildfires?
-	How does recovery vary based on land management practices? 

**Objectives**
-	We will use normalized differenced vegetation index (NDVI) to quantify vegetation recovery of the Douglas Fire region which occurred due to a lightning strike in July 2013. 
-	We will separate this analysis based on land ownership separate by private and publicly (Bureau of Land Management) land.


**Datasets**:  
1. Landsat imagery (https://earthexplorer.usgs.gov/)
2. OneDrive with the images used and land management tif: https://uoregon-my.sharepoint.com/:f:/g/personal/jsheppar_uoregon_edu/EpYdj0p_VN9CqwNEzg8yqScBjhU-bb_SwtWlBKwlxS-t4w?e=8cqHDd
3. Land Status/BLM OR ownership (BLM arc services). To convert the data to a readable tiff we match color to ownership.
- Orange: Bureau of Indian Affairs
- Yellow: Bureau of Land Management
- White: Private (we lumped all private companies together)
- Blue: Oregon Department of Forestry
- Gray: Josephine Country Forestry (local goverment)
- Green: U.S. Forest Service
4. Land ownership map from Zald and Dunn 2018 - *Severe fire weather and intensive forest management increase fire severity in a multi-ownership landscape* (https://doi.org/10.1002/eap.1710)

**Tools and packages:** we will use: pandas, geopandas, xarray, matplotlib. Additionally, we will use google earth engine in google colab in python to extract Landsat 7 and Landsat 8 surface reflectance imagery.

**Methodology and approach**: NDVI analysis from satellite imagery over time. We used landsat 7 and landsat 8 surface refelctance imagery. 

**Outcomes and future work**: We will produced a percent vegetation cover of the landslide over time to track recovery after disturbance. In the future we can connect this to change detection data using a five year data set.

**References**:
Schuster, Robert L., and Highland, Lynn M., (2004). Impact of landslides and innovative landslide mitigation measures on the natural environment: International Conference on Slope Engineering, Hong Kong, China, December 8–10, 2003, keynote address, Proceedings 29.

Zald, H.S.J., Dunn, C.J., 2018. Severe fire weather and intensive forest management increase fire severity in a multi-ownership landscape. Ecol Appl 28, 1068–1080. https://doi.org/10.1002/eap.1710