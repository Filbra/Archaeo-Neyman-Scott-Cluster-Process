# Spatial Humanities: the application of Neyman-Scott Cluster Process in landscape archaeology
---
This R script code was developed by dr. F. Brandolini (Newcastle University, UK) to accompany the paper: *Costanzo S., Brandolini F., Ahmed H., Zerboni A., Manzo A - Creating the funerary landscape in eastern Sudan*, submitted to Scientific Reports, 20XX.

The original dataset was compiled by S. Costanzo (Università di Napoli “L’Orientale”, Italy) as part of his PhD project within the frame of the IAEES - Italian Archaeological Expedition to the Eastern Sudan (Università di Napoli “L’Orientale”, Italy). The raster products (GeoTiff) were elaborated by dr. F. Brandolini with GRASS GIS and SAGA GIS software. This research was supervised by prof. Andrea Zerboni (Università degli Studi di Milano, Italy) and prof. Andrea Manzo (Università di Napoli “L’Orientale”, Italy).

Funeral landscapes are a specific example of archaeological landscapes that embed the relationship between environment, burials and human behaviour. In this study, we employ the 
Point Pattern Analysis (PPA) technique to explore the choice of location of a desk-created dataset of several thousands stone-built medieval Islamic funerary monuments (qubbas), 
found along the foothills of isolated rocky outcrops in the remote semi-arid Kassala province of Eastern Sudan. In the region a comprehensive geomorphological and geoarchaeological survey was carried out in the field to assess the main archaeological features, highlighting the existence of an impressive number of archaic and modern qubbas, whose spatial distribution can be interpreted using specific tools, including, for the first time in archaeology, of the Neyman-Scott Cluster Process.

## Archaeological Sites Dataset creation

The dataset explored in this research has been compiled adopting a remote sensing approach. In particular, free-open access satellite imagery collections were manually explored through the plugin QuickMapServices (NextGIS, 2019) in the GIS software QGIS 3.4 (QGIS Development Team, 2019). A 5 x 5 km grid was superimposed to the study area, which hereafter will be referred to as ROI (Region of Interest), to guarantee an orderly examination, gradually marking the completed squares. Adequate symbology was used for different kinds of archaeological evidence, manually and individually pinpointing all the recognizable features. Terrain surveys have been conducted in sampled areas of the ROI to validate the archaeological features detected through remote sensing observation.

## Point Pattern Analysis (PPA)

PPA (Baddeley, A., Rubak, E., Turner, R., 2015) has been performed using the package spatstat (Baddeley and Turner, 2005) within the software system 
for statistical computing R (R Core Team, 2019) through the visual interface of Rstudio (RStudio Team, 2019).


## List of files: 
R_script_code named "PPA_qubbas" in .rmd and .html formats.

Dataset available on Zenodo: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4384807.svg)](https://doi.org/10.5281/zenodo.4384807)

## Acknowledgements
This research was carried out as part of S.C.’s PhD project within the frame of the IAEES - Italian Archaeological Expedition to the Eastern Sudan. The IAEES is funded by the Università di Napoli “L’Orientale”, ISMEO - Associazione Internazionale di Studi sul Mediterraneo e l’Oriente, and the Italian Ministry of Foreign Affairs. The Expedition is also generously supported by the Regional Government of the Kassala State. Additional financial support was provided by Italian Ministry of Education, University, and Research (MIUR) through the project ‘Dipartimenti di Eccellenza 2018–2022’ (WP4—Risorse del Patrimonio Culturale) awarded to the Dipartimento di Scienze della Terra ‘A. Desio’ University of Milan, Italy). All authors wish to thank the archaeological authorities of the Republic of the Sudan, the National Corporation for Antiquities and Museums, the Ministry division in Kassala, their welcoming staff and the skilled drivers who made the field surveys possible.  Finally, the authors thank Prof. Francesco Carrer (Newcastle University, Newcastle upon Tyne, UK) for his comments on the R script code, and Prof. Isaac Ullah (San Diego State University, San Diego, CA - USA) for his suggestions on the use of the Cumulative Viewshed Analysis Grass GIS module.

## Corresponding authors:
- R script code: dr. Filippo Brandolini (McCord Centre for Landscape - School of History, Classics and Archaeology, Newcastle University, Armstrong Building, Newcastle upon Tyne - NE1 7RU)
- GeoTiff products: dr. Filippo Brandolini (McCord Centre for Landscape - School of History, Classics and Archaeology, Newcastle University, Armstrong Building, Newcastle upon Tyne - NE1 7RU)
- Archaeological sites datasets: Stefano Costanzo (Dipartimento Asia, Africa e Mediterraneo, Università degli Studi di Napoli "L'Orientale", Napoli, Italy)

## Contacts:
F. Brandolini: filippo.brandolini@newcastle.ac.uk
S.Costanzo: ste.costanzo92@gmail.com

## Cite as

Filippo Brandolini. (2021, January 4). Spatial Humanities: the application of Neyman-Scott Cluster Process in landscape archaeology (Version 1.0.0). Zenodo. http://doi.org/10.5281/zenodo.4384807

## References

- Baddeley, A., Turner, R., 2005. spatstat: An R Package for Analyzing Spatial Point Patterns. Journal of Statistical Software, Articles 12, 1–42.
- Baddeley, A., Rubak, E., Turner, R., 2015. Spatial Point Patterns: Methodology and Applications with R. CRC Press.
- Costanzo, S. et al. 2021. Geomorphology and palaeohydrography of the Southern Atbai Plain and western Eritrean Highlands (Eastern Sudan/Western Eritrea). J. Maps (2021)                      doi:10.1080/17445647.2020.1869112
- NextGIS, 2019. QuickMapServices https://nextgis.com/blog/quickmapservices/.
- QGIS Development Team, 2019. QGIS Geographic Information System. Open Source Geospatial Foundation Project.
- R Core Team, 2019. R: A language and environment for statistical computing. R Foundation for Statistical Computing. Vienna, Austria.
- RStudio Team, 2019. RStudio: Integrated Development for R. RStudio, Inc., Boston, MA.
