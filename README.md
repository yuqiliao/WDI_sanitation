# WDI_sanitation

This repository documents my attempt to create a quick analysis using World Bank API and my response to a statement about World Bank's retirees.

- `part1_output.Rmd`: 
  - It contains script to retrieve, manipulate, and visualize data, as well as the write-up of the analysis. Knitting this `.Rmd` file will produce `part1_output.html`
- `part1_output.html`: 
  - It is a client-facing document that includes the animation.
- `Part 2.docx`: 
  - It contains my response to a statement about World Bank's retirees.
  
- `sanitationData.rds`
 - This file is included as the backup data file, in the event the API used in the `part1_output.Rmd` stops functioning (which happened to me during development). 
- `GIFOutput/sanitation.gif`
 - When using `part1_output.Rmd` to produce `part1_output.html`, an animation (gif) file should be created and sourced from your local directory (not from this file). This file is just a backup in the unlikely event that the `part1_output.html` is not produced correctly in your local setting.   
