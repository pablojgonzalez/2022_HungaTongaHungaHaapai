# 2022_HungaTongaHungaHaapai
This is an open and reproducible repository of the scripts (Jupyter Notebooks) used to obtain and process GEOS satellite data 
to study the tsunami triggered by the January 2022 Hunga-Tonga Hunga-Haapai eruption presented in Omira et al., (2022) paper. 
We share these notebooks with our best intentions, but we do not accept any responsability for their usage.

If you use this in a scientific paper, we will appreciate a citation to the paper:

Omira, R., Ramalho, R.S., Kim, J., Gonzalez, P.J., Kadri, U., Miranda, J.M., Carrilho, F., Baptista, M.A., (2022) Global Tonga tsunami explained by a fast-moving atmospheric source. *Nature*, doi:[10.1038/s41586-022-04926-4](https://doi.org/10.1038/s41586-022-04926-4).


# Installation 

To run the scripts, you need some python packages with its dependencies. The simplest way to get up and running is to [create an anaconda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).
If you do not use Anaconda, you can learn about the dependencies in the ``goes_sat_environment.yml`` file from this repository.

## Jupyter Notebooks
- 00_Download_GEOS_satellite_data.ipynb - Download and store data locally for usage by the additional notebooks.
- 01_Merge_GOES16_GEOS17_and_plot.ipynb - Merge files from different satellites into a single map.
- 02_IRchannelsGOES17_Tonga_Explosion_Region.ipynb - Zoom in the Tonga eruption region
- 03_Make_Animated_GIFs_FullDisk_GOES_Data.ipynb - Create animated GIFs based on images from notebook 01 and/or 02.
- 04_TimeSeries_Specific_Locations.ipynb - Time series of 10-min differential brightness temperature at specific locations.
