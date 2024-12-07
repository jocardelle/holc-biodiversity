# Redlining and its effects on biodiversity in Los Angeles County

## About
Redlining refers to a practice by the Home Owners' Loan Corporation(HOLC) that dates back to the 1930's. The HOLC would rate neighborhoods (A - green, B - blue, C- yellow, or D - red) by "residential security" in various American cities. These ratings were often based on racial segregation and would then block access to loans for homeowners ([Gee, G.C.](https://pmc.ncbi.nlm.nih.gov/articles/PMC1447127/)). In this analysis we will explore the effects of redlining on health, economy, and environment today.


## Highlights
- Map making using `tmap`
- Manipulating vector and raster data to build multi-layer maps
- Data visualizations using `ggplot`
- Custom warning messages


## Repository Structure
```
|── holc-biodiversity 
|└── README.md
|└── holc-biodiversity.html
|└── holc-biodiversity,qmd  
|└── holc-biodiversity.Rproj
|└── holc-biodiversity_files
|  └── figure-html/
|    └── unnamed-chunk-4-1.png
|    └── unnamed-chunk-4-2.png
|    └── unnamed-chunk-4-3.png
|    └── unnamed-chunk-4-4.png
|    └── unnamed-chunk-7-1.png
|    └── unnamed-chunk-7-2.png
|  └── libs/
|    └── bootstrap/
|      └── bootstrap-icons.css
|      └── bootstrap-icons.woff
|      └── bootstrap.min.css
|      └── bootstrap.min.js
|    └── clipboard/
|      └── clipboard.min.js
|    └── quarto-html/
|      └── anchor.min.js
|      └── popper.min.js
|      └── quarto-syntax-highlighting.css
|      └── quarto.js
|      └── tippy.css
|      └── tippy.umd.min.js
|└── .gitignore  
|  └── data/ 
|  └── .Rproj.user
|  └── .Rhistory
|  └── .Rdata
|  └── .Ruserdata
```


## Data
Three datasets were used in this analysis. The first dataset is form the United States Environmental Protection Agency’s EJScreen: Environmental Justice Screening and Mapping Tool. It provides environmental and demographic information for US Census tracts and block groups. It can be downloaded at the [EPA website](https://www.epa.gov/ejscreen/download-ejscreen-data).

The second dataset is from the [Digital Scholarship Lab](https://dsl.richmond.edu/) at University of Richmond and can be downloaded [here](https://dsl.richmond.edu/panorama/redlining/data). It provides information on HOLC grades and we use it to determine grades in LA County.

The third dataset we worked with was from the [Global Biodiversity Information Facility](https://www.gbif.org/) and provides information on bird observations in LA County.


## References
1. Digital Scholarship Lab. Redlining Map Data (JSON file). University of Richmond, Digital Scholarship Lab. Accessed October 17, 2024.

2. Global Biodiversity Information Facility. (Data File) Available from https://www.gbif.org/ Access date: October 17, 2024.

3. United States Environmental Protection Agency. 2023. Data from: Geodatabase of National EJScreen Data at the Block Group Level

4. Gee, G. C. (2008). A multilevel analysis of the relationship between institutional and individual racial discrimination and health status. American journal of public health, 98(Supplement_1), S48-S56

5. Ellis-Soto, D., Chapman, M. & Locke, D.H. Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nat Hum Behav 7, 1869–1877 (2023). https://doi.org/10.1038/s41562-023-01688-5
