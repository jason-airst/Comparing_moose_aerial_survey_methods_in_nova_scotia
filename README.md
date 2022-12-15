# Comparing Moose Aerial Survey Methods in Nova Scotia: Distance Sampling, Density Surface Models, and Stratified Random Block Surveys
## Suplimentary Materials
## List of files:
### 1) R_code - R markdown file containing the code use to analyze data in the paper
#
### 2) Distance_2020 - Distance sampling data used to generate moose estimates via traditional distance sampling. Data also used to generate detection curves for density surface models
#### Sample.Label - Survey line number
#### Effort - length of survey line
#### Regional.Label - Region of survey line
#### Area - Area of region
#### Object - Unique group number. In this case the group's GPS waypoint number
#### size - Group size
#### distance - Distance group was from the survey line when first seen
#### Activity - Group's activity when first seen
#### CRNCL - Percent crown closure where the group was first seen
#
### 3) Seg_2020 - Distance sampling segment data used to generate moose estimates via a density surface models
#### Sample.Label - Survey line number
#### Transect.Label - Survey line segment number
#### Effort - length of survey line segment
#### X - Line segment centroid X coordinate 
#### Y - Line segment centroid Y coordinate 
#### Forest_type - Habitat type (non-forest, softwood, hardwood, mixed wood) of line segment centroid 
#### For_non - Habitat type (non-forest, forest) of line segment centroid 
#### Near_Road - Distance from line segment centroid to nearest road
#### Near_Water - Distance from line segment centroid to nearest surface water feature
#
### 4) Obs_2020 - Distance sampling observation data used to generate moose estimates via a density surface model

### 5) Pred_2020 - 1 km^2 grid of study area used to generate moose estimates from the density surface model created
### 6) Trans_2020 - Transect flight data used to stratify survey units into low, medium, or high density strata as part of the stratified random block survey
### 7) Strat_2020 - Statification flight data used to generate moose estimates via stratified random block survey method
### 8) Intensive_2020 - Intensive statification flight data used to generate sightability correction factors for the stratified random block survey method
