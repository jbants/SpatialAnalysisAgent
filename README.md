![icon - Copy.png](icon%20-%20Copy.png)
# SpatialAnalysisAgent  
The Spatial Analysis Agent is a user-friendly plugin that serves as a "Copilot" in QGIS software. This Copilot allows users to perform geospatial analysis directly within QGIS using natural language queries, making it accessible for both experts and beginners.

The plugin leverages the full potential of over 600 QGIS processing tools, including GDAL and GRASS GIS tools, and other external tools such as Python libraries (e.g., Geopandas, seaborn, etc.). Whether working with vector data, raster analysis, the Spatial Analysis Agent offers a flexible, AI-driven approach to enhance and automate GIS workflows.
 

# Installation
- [Download](https://github.com/Teakinboyewa/SpatialAnalysisAgent/archive/refs/heads/master.zip) the master repository of the plugin from github
- Launch QGIS software and navigate to ```Plugin >  Manage and install Plugins.. > Install from ZIP```
- Click on ```...``` to select the directory of the downloaded zip file and ```Install plugin```

# User Manual
The User Manual is available [here](https://github.com/Teakinboyewa/SpatialAnalysisAgent/blob/master/User_Manual.md)

# Plugin Interface

![Plugin Interface.png](Doc%2FPlugin%20Interface.png)

![Settings.png](Doc%2FSettings.png)

Note: API keys input here will only be stored locally on the user's computer ('plugin_dir/SpatialAnalysisAgent/config.ini').  

# Usage
Find some case studies on the [Case Studies](https://github.com/Teakinboyewa/SpatialAnalysisAgent/blob/master/Case_Studies.md) page


# Installing required libraries
## Required python libraries
- ```openai```
- ```QSwitchControl```
- ```nest-asyncio```

**Note:** You may need to install some other python libraries that may not be present in your QGIS environment. Follow the steps below to install the libraries mentioned or others

### Libraries installation guide
Using 'openai' as an example, follow these steps to install any python library:
- Open the QGIS Python Console by navigating to ```Plugins``` > ```Python Console``` or press ```Ctrl+Alt+P```
- In the console, run these two lines of code sequentially:
  ```python
  import pip
  pip.main(['install', 'openai'])
