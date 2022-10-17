# ATMS 523 Module-3

This project uses [ERA-5 monthly mean data from the NCAR Research Data Archive](web address) to calculate monthly mean SST and precipitation anomailes for the years 1979-2021 over the Pacific Ocean. These monthly anomalies are deseasonalized, detrended, and standardized in order to perform EOF analyses. 

## Setting Up
Other than some basic python packages like numpy and matplotlib, this project requires cartopy, pandas, dask, xarray, and eofs to run. To install these pacakges using conda, execute the following commands in your environment:
    
    conda install cartopy
    conda install pandas
    conda install dask
    conda install xarray
    conda install -c conda-forge eofs

## How to Use
Run the python jupyter notebook project4_atms523_blind.ipynb. There are 6 different parts to this project and markdown cells/comments detail each part of the project in the jupyter notebook.

## Citation Information
European Centre for Medium-Range Weather Forecasts, 2019: ERA5 Reanalysis (0.25 Degree Latitude-Longitude Grid). Research Data Archive at the National Center for Atmospheric Research, Computational and Information Systems Laboratory, Boulder, CO. [Available online at https://doi.org/10.5065/BH6N-5N20.] Accessed† 14 10 2022.

For part 1, the [Computations and Masks with Xarray documentation from Project Pythia](https://foundations.projectpythia.org/core/xarray/computation-masking.html) was used for help on calculating the SST and precipitation anomalies.

For part 2, the [Monthly data analysis — PyCLIM_101 0.2 documentation](https://climate.usu.edu/people/yoshi/pyclm101/monthly.html) was used for the detrend function.

## Maintenance of Project
This project was created for the University of Illinois ATMS 523 Weather and Climate Data Analytics course. The project is completed at this time.
