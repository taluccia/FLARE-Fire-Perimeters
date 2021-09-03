# FLARE-Fire-Perimeters

## Overview
This repository contains scripts for processing spatial data to develop a fire perimeter database for 8 ecozones across Northeastern Siberia. All reomte ssensing Landsat imagery processing occured in Googel Earth Engine.


## Scripts

Develop fire perimeters from Landsat data

1.1-EcozoneSelection
1.2-CreatingRegionsOfInterest
1.3-HotspotMarchOctober
1.4-HotspotToPolygon
2.1-GEE-Part1BinaryImage
2.2-GEE-Part2Vectorize
3.1-ShapefileClean
3.2-ShapefileAdvanceClean
3.3-AttributeCreation
3.4-RenameAttributes
3.5-CombineAllFires


## Final Attributes

Attribute	    |         Description       
------------- | ---------------------------
IDobj	        | Numberis ID	
FID	          | Numeric ID	
SIZEm2	      | Area of fire perimeter measured in squared meters	
SIZEha	      | Area of fire perimeter measured in hectares	
FireYr	      | Fire year	
EcoName	      | Ecozone name	(Olson et al. 2001)
EcoRlm	      | Code for Biogeographic realm PA refers to Palearctic	(Olson et al. 2001)
EcoBiom	      | This a a numeric ID 6 for taiga and 11 for tundra	(Olson et al. 2001)
EcoKm2	      | The area of the ecozone in kilometers  squared	(Olson et al. 2001)
EcoCode	      | Unique code associated with each ecozone.	
ArcSub	      | Location designation of Arctic or Subarctic	
MinDay	      | The minimum Julian associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MaxDay	      | The maximum Julian associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
AvgDay	      | The mean Julian associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MedDay	      | The median Julian associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MinConf	      | The minimum confidence value associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MaxConf	      | The maximum confidence value associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
AvgConf	      | The mean confidence value associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MedConf	      | The median confidence value associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MinDate	      | The minimum calendar date associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	
MaxDate	      | The maximum calendar date associated with the fire based on MODIS point thermal annomalies (i.e., hotspots)	


## References
**Hotspot point Shapefile**

[FIRMS](https://firms.modaps.eosdis.nasa.gov/download/create.php)

**Ecozone Shapefile**

Olson, D. M., Dinerstein, E., Wikramanayake, E. D., Burgess, N. D., Powell, G. V. N., Underwood, E. C., D'Amico, J. A., Itoua, I., Strand, H. E., Morrison, J. C., Loucks, C. J., Allnutt, T. F., Ricketts, T. H., Kura, Y., Lamoreux, J. F., Wettengel, W. W., Hedao, P., Kassem, K. R. 2001. Terrestrial ecoregions of the world: a new map of life on Earth. Bioscience 51(11):933-938.
[Download location ](https://www.worldwildlife.org/publications/terrestrial-ecoregions-of-the-world)

