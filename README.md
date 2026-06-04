# Maternal Adverse Events and Adverse Events of Special Interest during pregnancy

This study estimates incidence rates and cumulative incidence of selected adverse events during pregnancy, and characterise pregnancies with these events. The protocol for this study is registerd in the EMA RWD catalogue, with EU PAS number [EUPAS1000000712](https://catalogues.ema.europa.eu/node/4615/administrative-details).

## To run the study code
1. Open in Rstudio the Study.Rproj project (located in the Study folder).
2. Rebuild the R-environment from the provided lock-file in renv.lock with `renv::restore()`.
3. Restart de RSession and open the script `CodeToRun.R`. Fill the infromation in the script and set it to run.
4. When finished, you should expect a Results folder with a set of `.csv` files inside.

## To deploy the shiny
1. Open in Rstudio the shiny.Rproj project (located in the shiny folder).
2. Rebuild the R-environment from the provided lock-file in renv.lock with `renv::restore()`.
3. Restart R. Copy-paste the .csv files in the study results folder to the "data" folder in the shiny directory.
4. Run the preprocess.R script in the "data" folder.
5. Open the "global.R" script and run the app (top-left button in the R the script).
