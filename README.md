2. Set Up/Installation

2.1 Usage


This code will  use pre and post fire Landsat images over the Chrome 2 Fire to classify the burn severity in the region. Generally, it is advised that pre and post fire images are Landsat 7 or Landsat 8. The images used were Landsat 8 during this project and this type of imagery is preferred. 


2.2 Inputs


4.	Fire Perimeter shapefile
5.	Study Area Shapefile
6.	Pre and Post Fire Data placed into separate folders


2.4 Script Descriptions

Code Submission Final.ipynb
This script creates dNBR raster using both the Pre and Post Fire Landsat Imagery. 


2.5 Environment Set Up 


To first set up the environment you will need to fork the “Programming for Remote Sensing” repository to your own computer. Once this has been completed, the next step is to open the Anaconda Navigator, and click on the “Environments tab”. From here, you will click the import button located on at the bottom of the page. A dialogue box will then open asking you to select an environment.yml file. Navigate to the environment.yml file that was forked from the project repository and click “Import”. This should result in a new environment with the required packages being installed. For troubleshooting advice regarding the environment set up, please see section 5 of the "How to Guide".

2.6 Jupyter Notebook Set Up 


After the environment has been created for the project, the next step is to set up the Jupyter Notebook. It is recommended that you set up a separate folder for the project within Jupyter Notebook to avoid any confusion. The first step is to add all the necessary files for the project into the project area. It is recommended to create separate folders for both pre and post Landsat images, as they will be used separately within the code itself. An example of how I set up the Jupyter Notebook can be seen in figure 1 of the "How to Guide". Once the notebook has been set up correctly, you can begin writing the python script. 

 


2.7 Dependencies


  - python=3.8.8
  - geopandas=0.9.0
  - cartopy=0.18.0
  - notebook=6.2.0
  - rasterio=1.2.0
  - matplotlib 3.3.4
  - seaborn 0.11.1
  - numpy 1.20.1
  - Shapely 1.7.1
  - xarray 0.17.0
  - rioxarray 0.3.1
  - earthpy 0.9.2


2.11 Data
The data used for this project was collected from the USGS Earth Explorer online platform. This data represents an area over Glen County in California.  

2.12 Data included: 


The project data was downloaded from USGS using the following Landsat data code: 


•	L: Landsat Sensor
•	C: OLI/TIRS combined platform
•	08: Landsat 8 
•	Path/ Row: 45033
•	Before Date: 8th of September 2018
•	After Date: Any Date in 2019 can be used


For  this project, the Landsat data was clipped using the study area shapefile using the Erdas Imagine  software. This was completed to avoid any processing issues with the size of the Landsat files. The study area shapefile can be found in the GitHub repository.  
