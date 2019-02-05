# CulvertModel_2.0
Updated Cornell Culvert Model files

Feb 5, 2019
Updates and notes by Jo Archibald (jaa78@cornell.edu). 

This is an update that allows for more streamlined and consistent use of the Cornell Culvert Model.  It does not update any of the calculations in the python files. There are three major differences from the previous version:

1. File set-up
- In this version, the user should save the CulvertModelFiles folder containing the CulvertModel ArcGIS Toolbox and Python scripts in the same directory as their project files, NOT within each project folder (as was done previously).  This prevents the user from having to duplicate scripts and tools that are used for all projects.   
- The folder "GIS_files" should be copied into each project folder - this is where the GIS files and ArcMap document specific to the particular project will live.

2. Culvert Model Arc Toolbox:
- The tools have been updated to include some steps that had previously been done manually (e.g. burning streams into the DEM, resampling the CN file).  
- It also combines all the tools into one master tool called 01_Culvert_Watershed_Model, and adds a quick preprocessing tool called 00_clip_files. 

3. Python Scripts:
The python scripts have been modified slightly, to allow a little more flexibility in input data formatting, and to simplify the user experience running the files. Expect more changes here soon.  

