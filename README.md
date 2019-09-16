# WildfireConditionClass

Data Sources
counties
	Description: shapefile containing counties of US (polygon data)
	Source: Esri, TomTom North America, Inc., U.S. Census Bureau, U.S. Department of Agriculture (USDA), National Agricultural Statistics Service (NASS)
	Download Link: https://www.arcgis.com/home/item.html?id=a00d6b6149b34ed3b833e10fb72ef47b
	Organization/Manipulation: Extracted data download into folder 'USA_Counties'. Desired data for model input is in USA_Counties > v106 > counties.gdb
us_140vcc
	Description: Vegetation Condition Class data for US (raster data)
	Source: Landfire (https://www.landfire.gov/vcc.php) 
	Download Link: https://www.landfire.gov/version_comparison.php
	Organization/Manipulation: Downloaded all US data for LF 2014 (LF 1.4.0). Extracted data download into folder 'US_140VCC_20180620'. Desired data for model input is US_140VCC_20180620 > Grid > us_140vcc


Folder/File Descriptions
Intermediates
	Description: Folder created to hold intermediate data products for processing steps

FinalOutputs
	Description: Folder created to hold final data products including zonal stat tables for each vegetation condition class. Each zonal stat file contains an excel sheet with cell counts for each VCC.

WildfireConditionClassToolbox.tbx
	Description: Toolbox containing model for processing wildfire condition class data.

WildfireConditionClassModel
	Description: ArcGIS model built to process Landfire VCC data in built environment.
