# Group_19_project: A study of early predictors (Comorbidities and Etiology) of cirrhosis' patients mortality

## Project Contributors

-   Pauline Charpentier - @Linepocharpe - s231663
-   Eva Frossard - @EvaFrossard - s231701
-   Noy Tabul - @NoyTii - s232743
-   Fabian Ziegler - @fabianhz1 - s231932

## Dataset

Our project is based on the study of the following dataset: Mukthinuthlalapati, VV Pavan Kedar et al. (2019). Data from: Early predictors of outcomes of hospitalization for cirrhosis and assessment of the impact of race and ethnicity at safety-net hospitals [Dataset]. Dryad. <https://doi.org/10.5061/dryad.6gt88dv> We discarded the the race and ethnicity variable since they were considered non-significant variable to determine patient's outcome. We, therefore, chose to focus ouor study on Comorbidities and Etiology, and their according numerical value: Child Pugh Score (CPS) and Charlson Comorbidity Index.

## To load the dataset onto the project

1)  Create a /data folder in the project
2)  Go to the website where the dataset can be found (<https://doi.org/10.5061/dryad.6gt88dv>) and download the .csv file
3)  Upload it in the /data folder

## Packages to install

Before running the files that can be found in the "R" folder, a few packages should be installed and the following command lines should be run in your console:

-   `install.packages('tidyverse')`
-   `install.packages('ggplot2')`
-   `install.packages('ggpubr')`
-   `install.packages('forcats')`

## Structure of the project

-   [00_all.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/00_all.qmd): run-all file of the project. Used to render all of the subfiles.
-   [01_load.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/01_load.qmd):loading of the files. Write in the [/data](https://github.com/rforbiodatascience23/Group_19_project/blob/main/data) folder : 01_dat_load.tsv
-   [02_clean.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/02_clean.qmd): tidying of the dataset. Write in the [/data](https://github.com/rforbiodatascience23/Group_19_project/blob/main/data) folder : 02_dat_clean.tsv
-   [03_augment.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/03_augment.qmd): augmentation of the dataset, creation of new variables. Write in the [/data](https://github.com/rforbiodatascience23/Group_19_project/blob/main/data) folder : 03_dat_augment.tsv
-   [04_describe.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/04_describe.qmd): creation of introduction graphs giving general statistic information about the dataset.
-   [05_analysis_CPS.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/07_analysis_CPS.qmd): determining if the different comorbidities and etiologies have an impact on the Child Pugh Score.
-   [06_analysis_mortality.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/06_analysis1.qmd): analysis of the patients' mortality and the different variables affecting it.
-   [07_analysis_comorbidities_etiologies.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/07_analysis_comorbidities_etiologies.qmd): investigating the relation between comorbidities and the patient's liver disease.
-   [08_analysis_liver_disease.qmd](https://github.com/rforbiodatascience23/Group_19_project/blob/main/R/08_analysis_liver_disease.qmd): linear regression model to see how the different liver diseases affect mortality.
