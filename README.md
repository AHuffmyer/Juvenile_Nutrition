
**Study:** Heterotrophy and thermal conditioning enhance coral temperature tolerance in juvenile *Pocillopora acuta*  

**Authors:** Ariana S. Huffmyer, Colton J. Johnson, Ashleigh M. Epps, Judith D. Lemus, Ruth D. Gates

**Corresponding Author:** Ariana S. Huffmyer, ashuffmyer@gmail.com

Data in this repository are analyzed using an R Markdown script. Data files are found in the "Data" folder and output files are generated and stored in the "Output" folder. Figures are generated into the "Figures" folder. The R Markdown analysis is available for viewing as an HTML document.  

**Data Files:**  

*Temperature.csv* - Temperature data recorded by Apex Neptune system every 15 minutes during rearing and stress period of experiment.  

*Larval_Settlement.csv* - Settlement of larvae in cool and ambient temperature treatments on each plug "Plug.ID". Cohort indicates day of larval release from parent colony. Larvae indicates total larvae at the start of the settlement trial. Success = number of settlers. Failures = number of swimming or dead (non-settled) larvae.  

*Rearing_Survivorship.csv* - Survival measurements at each date on each PlugID during the rearing treatment period. Survivorship of 1 indicates at least one living juvenile was recorded on the plug. Censor is used in Cox PH model with a value of 0 indicating at least one living juvenile recorded on the plug and a value of 1 indicating complete mortality. Time indicates ordered timepoint and days indicates days post-settlement.  

*Colony_Growth.csv* - Total planar surface area of each juvenile, denoted by "Plug.ID" and "Colony.ID", measured over the course of the rearing period ("StartDate" - "EndDate"). "Fused.Initial" and "Fused.Final" indicates whether juvenile was fused with others at the start of the rearing period. Growth is recorded as "Area" and "Polyps" were area is planar surface area measured by ImageJ. Days indicates the time between start and end measurements.  

*Colony_Area.csv* - Total planar surface area of juveniles sampled for laser scanning confocal microscopy measurement of tissue thickness and Symbiodiniaceae fluorescence. Juvenile indicated by "Sample". Surface area is used here as a covariate in analysis of physiological measures.  

*Symbiont_Fluorescence.csv* - Symbiodiniaceae fluorescence of each juvenile sample by laser scanning confocal microscopy at the end of the rearing period. Value used for calculation of symbiont fluorescence is "Symbiont.Intensity" taken at multiple locations on each juvenile. 

*Tissue_Thickness.csv* - Tissue thickness measurements of each juvenile sample by laser scanning confocal microscopy at the end of the rearing period. Value used for calculation of tissue thickness is "Thickness" taken at multiple locations on each juvenile.    

*NOAA_June17.csv* - Environmental data collected by NOAA (NOAA Moku o Loe station #51207, Pacific Islands Ocean Observing System) during June 2017 for comparison to rearing treatment conditions.  

*NOAA_March17.csv* - Environmental data collected by NOAA (NOAA Moku o Loe station #51207, Pacific Islands Ocean Observing System) during March 2017 for comparison to rearing treatment conditions.  

*Stress_Survival.csv* - Survivorship measurements at each timepoint on each plug during the thermal stress period. Survivorship measured as the number of live juveniles on each plug. Day indicates days of exposure during the thermal stress period. "Rear.Temp" indicates rearing temperature treatment.  

 

