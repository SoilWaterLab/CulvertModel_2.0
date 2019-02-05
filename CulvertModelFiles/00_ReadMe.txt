Created Jan 2019
Updated Culvert Model files to simplify running the model. V.2.0
Python Files and ArcToolbox all saved here, no need to recopy for each model run.
Python script requires that file structure will be:
Culvert folder --> CulvertModelFiles
	       --> Data folder --> GIS_files --> DEMs, Temp, WS_Poly, All_Culverts_Shapefile, ArcMap file
				--> NAACC, precip csv files
				--> Model output folder
Note - multiple data folders can be housed within the larger Culvert folder, with any edits made to the python/GIS files applying for all datasets.
Python script files need to be told the "Data folder" name, and assumes the csv files also include that name.
