# FLARE-Fire-Perimeters

## Overview
This repository contains scripts for processing spatial data to develop a fire perimeter database for 8 ecozones across Northeastern Siberia.

The paper can be found here

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


## Fire terminology

[Fire Effects Information System Glossary](https://www.fs.fed.us/database/feis/glossary2.html#1)

## References
**Hotspot point Shapefile**
[FIRMS](https://firms.modaps.eosdis.nasa.gov/download/create.php)

**Ecozone Shapefile**
Olson, D. M., Dinerstein, E., Wikramanayake, E. D., Burgess, N. D., Powell, G. V. N., Underwood, E. C., D'Amico, J. A., Itoua, I., Strand, H. E., Morrison, J. C., Loucks, C. J., Allnutt, T. F., Ricketts, T. H., Kura, Y., Lamoreux, J. F., Wettengel, W. W., Hedao, P., Kassem, K. R. 2001. Terrestrial ecoregions of the world: a new map of life on Earth. Bioscience 51(11):933-938.
[Download location ](https://www.worldwildlife.org/publications/terrestrial-ecoregions-of-the-world)

**Yedoma Shapefile**
Strauss, Jens; Laboor, Sebastian; Fedorov, Alexander N; Fortier, Daniel; Froese, Duane G; Fuchs, Matthias; Grosse, Guido; Günther, Frank; Harden, Jennifer W; Hugelius, Gustaf; Kanevskiy, Mikhail Z; Kholodov, Alexander L; Kunitsky, Victor V; Kraev, Gleb; Lapointe-Elmrabti, Lyna; Lozhkin, Anatoly V; Rivkina, Elizaveta; Robinson, Joel; Schirrmeister, Lutz; Shmelev, Denis; Shur, Yuri; Siegert, Christine; Spektor, Valentin; Ulrich, Mathias; Vartanyan, Sergey L; Veremeeva, Alexandra; Walter Anthony, Katey M; Zimov, Sergey A (2016): Database of Ice-Rich Yedoma Permafrost (IRYP), link to ESRI shapefiles. PANGAEA, https://doi.org/10.1594/PANGAEA.861732,

[Download location](https://doi.pangaea.de/10.1594/PANGAEA.861732)

**Permafrost Shapefile**
Brown, J., O. Ferrians, J. A. Heginbottom, and E. Melnikov. 2001. Circum-Arctic Map of Permafrost and Ground-Ice Conditions, Version 2. [Indicate subset used]. Boulder, Colorado USA. NSIDC: National Snow and Ice Data Center. doi: https://doi.org/10.7265/skbg-kf16. [Date Accessed].

[permafrost shapefile details](https://nsidc.org/data/GGD318/versions/2/print)
