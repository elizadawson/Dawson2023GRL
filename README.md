# Results from manuscript: Heterogeneous basal thermal conditions underpinning the Adélie-George V Coast, East Antarctica
\
If you are using this data, please cite Dawson et al., 2023, Heterogeneous basal thermal conditions underpinning the Adélie-George V Coast, East Antarctica, GRL\
\
ProcessedRadarData.csv contains the processed radar data used to make Figure 2d and 2e (maps of attenuation rate and relative reflectivity in the study area).\
For the processed data with both 1dB/km and 2dB/km requirement, the fields are:\
- x - coordinate location\
- y- coordinate location\
- atten_rate - attenuation rate\
- rel_ref - relative reflectivity\
- fitting_rad - the fitting radius needed to satisfy the goodness of fit conditions in the attenuation fitting method (Chu et al., 2021 and Schroder et al., 2016)\
\
StudyArea.txt contains the coordinates of the Study Area perimeter (see Fig. 1)\
\
LogRegPred_RelaxedProcessing.nc and LogRegPred_StrictProcessing contains the predictions (0 to 1) of the logistic regressions (the four panels in Fig. 3a)\
LogRegInterp.nc contain the linearly interpolated classifications (the four center panels in Fig. 3b) and the combined results shown in Fig. 3c made by thresholding and stacking the classifications.



