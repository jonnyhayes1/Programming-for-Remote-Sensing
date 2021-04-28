#Programming-for-Remote-Sensing-Project


2.1 Usage:


This tool will use a fire perimeter and use the pre and post fire Landsat images over the Fork Fire to classify the burn severity in the region. Generally, it is advised that post fire images are Landsat 7 or Landsat 8. The pre fire images used were Landsat 8 during this project and this type of imagery is preferred. 

2.2 Inputs:


1.	Fire Perimeter shapefile
2.	Study Area Shapefile
3.	Pre and Post Fire Data placed into separate folders

2.3 Script Descriptions


AssignmentScript.py
This script creates Difference Normalised Burn Ratio Rasters using both the Pre and Post Fire Landsat Imagery. 

2.4 Requirements:


Requires Erdas Imagine 2016, Arcpro 2.6, Jupyter Notebook. 

2.5 Getting Help or Reporting an Issue:


Please see Section 5 of this ‘How to Guide’ for advice for troubleshooting.

2.6 License:


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

The software is provided "as is", without warranty of any kind, express or
Implied, including but not limited to the warranties of merchantability,
Fitness for a particular purpose and noninfringement. In no event shall the
Authors or copyright holders be liable for any claim, damages or other
Liability, whether in an action of contract, tort or otherwise, arising from,
Out of or in connection with the software or the use or other dealings in the
Software.

https://opensource.org/licenses/MIT

2.7 Data:


The data used for this project was collected from the USGS Earth Explorer online platform. This data represents an area over the Sierra Nevada area of California.  
Data was collected from a variety of sources to create the necessary surfaces to perform this analysis. These include the California  state government, USGS, and the California city government.

2.8 Data included: 


The project data was downloaded from USGS using the following Landsat data code: 
•	L: Landsat Sensor
•	C: OLI/TIRS combined platform
•	08: Landsat 8 
•	Path/ Row: 45033
•	Before Date: 8th of September 2018
•	After Date: Any Date in 2019 can be used
