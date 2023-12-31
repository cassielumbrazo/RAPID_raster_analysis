# RAPID_raster_analysis
Cle Elum Ridge RAPID lidar data analysis\
October 2023\
Cassie Lumbrazo

### Notebooks
1_different_dtm_processing.ipynb
* I used different methods to classfy ground points from the RAPID point cloud data in Cloud Compare: set 1, set 2, and set 3
* In this notebook, we take a look at snow depth calculated from all three to see what is best to proceed with 

From here, I moved the snow depth rasters into ArcGIS Pro to take a closer look and remove some of the large tree piles from the datasets to continue using. I also used the ArcGIS Pro "Model" to create DCE from previous methods. 

2_rapid_model_create_netcdf.ipynb
* bring all the Cle Elum Ridge files, old and new, together into a single netcdf 
* clean up snow depth and dce (mask edges)

3_rapid_model_plots.ipynb 
* recreate some previous raster analysis plots 

4_rapid_compare_canopy_v1.ipynb
* compare chm and chmws from before and after treatments 
* also, compare the dce from my methods and Giulia's model methods for rapid data 
* includes a lot of aspect calculations before moving to dah

5_rapid_compare_canopy_v2.ipynb
* cleans up and adds to analysis in notebook 4 
* includes some aspect calculations, but also all the baf lidar change calculations 
* also includes the resampling to 20,000 points 

6_rapid_compare_canopy_v3.ipynb 
* cleans up and adds to analysis in notebook 5 
* removes the aspect calculations, keeps some of the baf calculations, but removes the resampling
* adds a lot more figures of the lidar data 
* and, total calculations of SWE


