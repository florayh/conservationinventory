# conservationinventory
Replication code for "An empirically driven and inclusive inventory facilitates recognition of diverse area-based conservation of nature"

Authors: Siyu Qin, Yifan He , Rachel E. Golden Kroner , Sushma Shrestha ,
Bruno Henriques Coutinho, Marion Karmann  , Juan Carlos Ledezma , Christian
Martinez, Vilisa Morón-Zambrano , Roberto Ulloa , Edgard Yerena , Curtis Bernard ,
Joseph W. Bull , Eddy Mendoza , Nyls de Pracontal, Katie Reytar , Peter Veit , Erik
Olsson , Clara L. Matallana-Tobón , Liz Alden Wily , Michael B. Mascia

Code written by Yifan He. 

Depdendencies: Code was written in R (4.3.2) 
Required R packages are tidyverse (2.0.0), readxl (1.4.3), paletteer (1.6.0) and RColorBrewer (1.1.3)

Data: Input data is available at https://dataverse.harvard.edu/...  (doi:10.7910/DVN/HHT0TN)

Summary of scripts: Code should be run in the following order:
1) Tables_Figures.Rmd: code to produce all quantitative tables and figures from pre-processed data. 

Pre-processing scripts are not included in this repository due to sharing restrictions of some source datasets.

Additional scripts available upon request:
1) area_calculations.R: calculate area by system subfamily/country/biome/land. 
2) compare_WDPA.R: compare category coverage of our 2016 Amazon dataset with the 2016 version of WDPA, and the 2023 version of WDPA + WD-OECM 
