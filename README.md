# Parameter/Fomulation Regionalization for NextGen

**Description**: NextGen regionalization is adapted from the NWM regionalization framework (see below), which uses a physical similarity-based approach to transfer model formulations and parameters from calibrated basins (donors) to uncalibrated areas (receivers). Currently, the framework considers two different sets of basin attributes to represent physical similarity: Hydrologic Landscape Regions (HLR, Winter 2001 and Wolock et al. 2004 ) and Catchment Attributes and Meteorology for Large-sample Studies (CAMELS, Addor et al. 2017). 

A few notes:

  - **Status**: Currently the framework focuses on regionalization in HUC-01; extending to the CONUS region might require adjustments to the scripts
  - **./scripts**: A collection of scripts related to computing catchment attributes and generating donor-receiver pairings 
  - **./fihm/scripts**: A collection of scripts related to generating ngen realization files and processing/analyzing the outputs for the FIHM AOP
 
**The NWM Regionalization Framework**

![Framework](https://github.com/NOAA-OWP/NextGen_Regionalization/blob/master/doc/Framework.png?raw=false)

## Dependencies

The scripts uses a series of R libraries including the zonal package in the [hydrofabric](https://github.com/NOAA-OWP/hydrofabric) tools 

## Credits and references

**Acknowlegement**: The NextGen regionalization framework was adapted from the NWM v3 regionalization work and has benefited from discussions and help from the NWM calibration team, as well as the valuable feedback from the RFCs.

**References**:

Addor, N., A.J. Newman, N. Mizukami, and M.P. Clark, 2017. The CAMELS data set: catchment attributes and meteorology for large-sample studies. Hydrol. and Earth Syst. Sci., 21, 5293-5313, doi:10.5194/hess-21-5293-2017

Winter, T. C. (2001) The concept of hydrologic landscapes. J. Am. Water Resour. Assoc. 37, 335–349.

Wolock, D. M., Winter, T. C. & McMahon, M. (2004) Delineation and evaluation of hydrologic-landscape regions in the United States using geographic information system tools and multivariate statistical analyses. Environ. Manage. 34, S71–S88.
