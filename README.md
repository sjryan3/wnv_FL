Sadie J. Ryan
September 19, 2025

Welcome! This is a repo for geospatial files, stored as GeoTIFFs, generated in R (ver 4.5.1) using 'terra'. They comprise 21 files for baseline and 20 future climate scenarios, for which we calcualted the months of transmission suitability for West Nile Virus (WNV) transmission, based on published estimates of thermal suitability for transmission by Culex quinquefasciatus mosquitoes (also known as southern house mosquitoes), for 30s resolution data, for Florida. For the 20 projected climate scenarios, we used 2 mitigation scenarios - SSP2-4.5 and SSP5-8.5, representing a mitigation and a no-mitigation trajectory. We used 5 general circulation models (GCMs) representing a range of projected climate outcomes, to combat the problem of 'hot models' that arose in response to IPCC findings using CMIP6 models. We used projections for 2021-2040 (2030), and 2041-2060 (2050), and follow the naming conventions of the midpoint year (2030, 2050).  

The file representing baseline months of suitability for transmission is named "FL_WC21_WNV_CQ_CURR_Sum.tif". The remaining 20 files follow a naming convention as such: fm_"SSP""GCM""Year"w_FL - e.g. fm245ACC30w_FL would be SSP2-4.5, using ACC model (see manuscript Methods), for the year 2030. 

Supplemental Data files for the manuscript are also housed in the repo: S1.csv containing the number of months of suitability at the county level at baseline climate; S2. csv containing the number of months of suitability at the county level for every combination of Year, GCM and SSP. 


The below is Figure 1 in the manuscript: the number of months of WNV transmission suitability at climate basline, by county, in FL. 
<img width="1918" height="1281" alt="wcurZplot" src="https://github.com/user-attachments/assets/edd6485a-b4f4-4da5-bdca-01aae48a9c66" />
