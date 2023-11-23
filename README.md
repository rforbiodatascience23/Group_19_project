# Group_19_project: A study of early predictors (Comorbidities and Etiology) of cirrhosis' patients mortality

## Dataset

Our project is based on the study of the following dataset: Mukthinuthlalapati, VV Pavan Kedar et al. (2019). Data from: Early predictors of outcomes of hospitalization for cirrhosis and assessment of the impact of race and ethnicity at safety-net hospitals [Dataset]. Dryad. <https://doi.org/10.5061/dryad.6gt88dv>
We discarded the the race and ethnicity variable since they were considered non-significant variable to determine patient's outcome. We, therefore, chose to focus ouor study on Comorbidities and Etiology, and their according numerical value: Child Pugh Score (CPS) and Charlson Comorbidity Index.


## To load the dataset onto the project

1)  Create a /data folder in the project
2)  Go to the website where the dataset can be found (<https://doi.org/10.5061/dryad.6gt88dv>) and download the .csv file
3)  Upload it in the /data folder

## Packages to install

Before running the files that can be found in the "R" folder, a few packages should be installed and the following command lines should be run in your terminal:

-   `install.packages('tidyverse')`
-   `install.packages('ggplot2')`
-   `install.packages('patchwork')`
