# UC_2018
Materials presented at Esri's 2018 UC


These notebooks were created in a conda environment set-up in the following fashion:

1)	Install R
2)	Install the R-ArcGIS Bridge
3)	Clone arcgispro-py3 environment: conda create --name arcgispro-r --clone arcgispro-py3
4)	Activate your new environment: activate arcgispro-r
5)	Install R-Essentials: conda install -c r r-essentials r-reticulate
6)	By default, the R version install is quite old. Update your packages: conda update --all
7)	Make sure your R version now it at least greater than 3.2.2
8) 	In ArcGIS Pro, make sure you set your environment to arcgispro-r in the Python Package Manager


To use these notebooks: 

1) Set-up the proper environment to run them in. 
2) Paste notebooks into that location. On my machine, that is: C:\ArcGIS\Pro\bin\Python\envs\arcgispro-r
3) Paste the data folder into that location as well. On my machine, that is: C:\ArcGIS\Pro\bin\Python\envs\arcgispro-r