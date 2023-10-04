# RAPID_raster_analysis
Cle Elum Ridge RAPID lidar data analysis\
October 2023\
Cassie Lumbrazo

### Notebooks
different_dtm_processing.ipynb
* I used different methods to classfy ground points from the RAPID point cloud data in Cloud Compare: set 1, set 2, and set 3
* In this notebook, we take a look at snow depth calculated from all three to see what is best to proceed with 

From here, I moved the snow depth rasters into ArcGIS Pro to take a closer look and remove some of the large tree piles from the datasets to continue using. I also used the ArcGIS Pro "Model" to create DCE from previous methods. 

rapid_model_create_netcdf.ipynb
* bring all the Cle Elum Ridge files, old and new, together into a single netcdf 
* clean up snow depth and dce (mask edges)


Then move to a plotting script to continue analysis on this dataset without needing to load rasters. 


