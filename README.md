# Comparing Moose Aerial Survey Methods in Nova Scotia: Distance Sampling, Density Surface Models, and Stratified Random Block Surveys
## Suplimentary Materials
## List of files:
### R_code - R markdown file containing the code used to analyze data in the paper
#
### Distance_2020 - Distance sampling data used to generate moose estimates via distance sampling. Data also used to generate detection curves for density surface models
#### Sample.Label - Survey line number
#### Effort - length of survey line
#### Regional.Label- Region of survey line
#### Area - Area of region
#### Object - Unique group number. In this case the group's GPS waypoint number
#### size - Group size
#### distance - Distance group was from the survey line when first seen
#### Activity - Group's activity when first seen
#### CRNCL - Percent crown closure where the group was first seen
#
### Seg_2020 - Distance sampling segment data used to generate moose estimates via a density surface models
#### Transect.Label - Survey line number
#### Sample.Label - Survey line segment number
#### Effort - length of survey line segment
#### X - Line segment centroid X coordinate 
#### Y - Line segment centroid Y coordinate 
#### Forest_type - Habitat type (non-forest, softwood, hardwood, mixed wood) of line segment centroid 
#### For_non - Habitat type (non-forest, forest) of line segment centroid 
#### Near_Road - Distance from line segment centroid to nearest road
#### Near_Water - Distance from line segment centroid to nearest surface water feature
#
### Obs_2020 - Distance sampling observation data used to generate moose estimates via a density surface model
#### Sample.Label - Survey line segment number
#### Object - Unique group number. In this case the group's GPS waypoint number
#### size - Group size
#### distance - Distance group was from the survey line segment when first seen
#
### Pred_2020 - 1 km^2 grid of study area used to generate moose estimates from the density surface model created
#### ID - Grid square number
#### area - Area of grid square
#### Regional.Label - Region of grid square
#### X - Grid square centroid X coordinate 
#### Y - Grid square centroid Y coordinate 
#### Forest_type - Habitat type (non-forest, softwood, hardwood, mixed wood) of grid square centroid
#### For_non - Habitat type (non-forest, forest) of grid square centroid
#### Near_Road - Distance from  grid square centroid to nearest road
#### Near_Water - Distance from grid square centroid to nearest surface water feature
#
### Stat_2020 - Stratification flight data used to stratify survey units into low, medium, or high density strata as part of the stratified random block survey
#### SU - Survey unit number
#### Area_km2 - Area of survey unit
#### Area_Park - Area of survey unit inside the Cape Breton Highland National Park
#### Region - Region of survey unit
#### Moose_Seen - Number of moose seen in transect flight over survey unit
#### Moose_Tracks - Number of moose tracks seen in transect flight over survey unit
#### Total_Moose_Estimate - Total moose estimate. Calculated by (Moose_seen + 0.25 * Moose_track) rounded to the nearest whole number
#
### Block_2020 - Block flight data used to generate moose estimates via stratified random block survey method
#### SU - Survey unit number
#### Stratum - Survey unit stratum (Low, Medium, High) calculated from the Strat_2020
#### Park - Was survey unit within Cape Breton Highland National Park
#### Area - Area of survey unit
#### Park_Area - Area of survey unit inside the Cape Breton Highland National Park
#### Moose - Number of moose seen in survey unit
#
### Intensive_2020 - Intensive Block flight data used to generate sightability correction factors for the stratified random block survey method
#### SU - Survey unit number
#### Stratum - Survey unit stratum (Low, Medium, High) calculated from the Strat_2020
#### Park - Was survey unit within Cape Breton Highland National Park
#### Moose - Number of moose seen in quarter section of survey unit during standard block survey
#### Moose - Number of moose seen in quarter section of survey unit during intensive block survey
