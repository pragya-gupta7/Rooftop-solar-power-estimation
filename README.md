# Rooftop-solar-power-estimation

### Defining AOI using WKT
It will make it easy to focus only on Area of Interest (AOI). Use this WKT tool: https://arthur-e.github.io/Wicket/sandbox-gmaps3.html

### Building footprints download
https://code.earthengine.google.com/51cd528a8cc77a980d72dc7adfb09ce0

In case, you face any difficulty in accessing the above link, you can refer the building_footprints_data_download.txt file for code which you can paste on Google earth engine code editor to download required data.

### Downloading DTM data
https://code.earthengine.google.com/b81be46608684b5a7356884414f2d066

In case, you face any difficulty in accessing the above link, you can refer the dtm_download.txt file for code which you can paste on Google earth engine code editor to download required DSM data.
After this, In ArcGIS pro, using Raster Calculator tool, Building footprints height is added to DTM to generate DSM data.

### Generation of DSM
https://code.earthengine.google.com/d3c8f811a2dd0b1218e018eb84a9ab0e

In case, you face any difficulty in accessing the above link, you can refer the dsm_generation.txt file for code which you can paste on Google earth engine code editor to download required DSM data.
