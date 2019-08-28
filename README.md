# GrasslandBirds
code and data to explore spatial patterns in grassland bird declines. Species trajectories from the R-package bbsBayes using the GAM model-option. Species inclusion based on the species in the State of Canada's Birds, monitored by the BBS.
This repository contains all the code and data required to re-create the slides in my Grassland Bird Symposium talk at the 2019, SCO-SOC meeting in Quebec City.

I'm providing these data and code to make them available to anyone working on understanding population declines in grassland birds, and in hopes that exploring these results will stimulate a collaboration to help better understand and fully describe these spatial, taxonomic, and temporal patterns. Please don't hesitate to contact me for more information or with questions. This is very-much a work in progress and there are many opportunities to diver deeper into these data and to expand this analysis to include other species (e.g., not everyone agrees on our definition of "grassland bird").

The file "Grassland regional exploration.r" is the main R-script. If all files are placed in a local directory, the script will run. It will create subdirectories for the output and install the necessary packages. It produces the main geofacet plots used in the presentation, as well as many regional and species-specific plots that are worth exploring.

NOTE: you will need to have JAGS installed on the computer. You should consider installing JAGS 4.2 software to run these analyses. JAGS 4.3 (the current version) is much less efficient with the class of models used here. https://sourceforge.net/projects/mcmc-jags/files/JAGS/4.x/Windows/


