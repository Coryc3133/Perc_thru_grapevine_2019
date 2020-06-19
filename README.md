# Perc_thru_grapevine_2019
Repository for Data &amp; Analyses in *Costello, C. K. &amp; Srivastava, S. (2020). Perceiving through the grapevine: A network approach to reputations.

* `Data/`folder contains the datasets
* `Plots/` contain images of the plots, though they are also contained in the knitted html.
* `big_six_evaluativeness_icc(.Rmd/.Html)` calculates the ICC for the evaluativeness ratings used in the profile analyses. 
* `data_subsetting_perceiving_through_grapevine_2019(.Rmd/.Html)` shows the subsetting of the data; it will not run as it requires access to the original datasets which we have not shared yet.
* `perceiving_through_grapevine_2019(.Rmd/.Html)` recreates every analysis, table, and plot in the MS and its supplements (as well as some additional Information, Tables & Plots) from the initial submission (available [here](https://costello.netlify.com/files/Perceiving_personality_through_grapevine_08.09.2019.pdf)).
* `perceiving_through_grapevine_2019_R-R(.Rmd/.Html)` recreates every analysis, table, and plot in the revised manuscript and its supplements (as well as some additional Information, Tables & Plots) from the revised submission.
* `perceiving_through_grapevine_2019_SAMs(.Rmd/.Html)` has the SAM results separately for Study 1 and study 2.

The repository contains everything sufficient to reproduce the analyses. If you open the R project and knit `perceiving_through_grapevine_2019.Rmd`, you should be able to exactly reproduce `perceiving_through_grapevine_2019.Html`, and all of the analyses, plots, and tables in the pre-print. If you knit `perceiving_through_grapevine_2019_R-R.Rmd`, you should be able to exactly reproduce `perceiving_through_grapevine_2019_R-R.Html`, and all of the analyses, plots, and tables in the revised manuscripts. You can reset the cache in R studio, but it will take some time to run the analyses without the cache.
