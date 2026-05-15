# Double-Edged Feed: The Dominant Role of Politics in Social Media Interaction & Preferences

This is the repository corresponding to the paper: “Double-Edged Feed: The Dominant Role of Politics in Social Media Interaction & Preferences“ by Jean Springsteen, Dino Christenson, and William Yeoh. The full paper can be found here: 

Included in this repository are the full, anonymized dataset resulting from the user survey, the code and methodology, and a copy of the survey. Below is an explanation of the files included. 

## R Markdown Files

- **0_Data_Anonymization.Rmd**: An R Markdown file that anonymizes the survey data. It does detail the steps we took to remove personally identifying information. Note: This will not run without the original survey data, which - for obvious reasons- is not provided in this repo.

- **1_Data_Cleaning.Rmd**: An R Markdown file that cleans the (anonymized) data and creates variables needed for the analysis. 

- **2_Double_Edged_Feed_Analysis.Rmd**: The R Markdown file where the conjoint analysis was performed, specifically using the `cregg’ package. This file also creates the images in the paper. 

## Data

- **anonymized_survey_data.csv**: The result of file 0_Data_Anonymization.Rmd. This contains all the data from the user survey, anonymized to protect user information. The anonymization process is detailed in the R Markdown file. 

- **cleaned_anonymized_survey_data.csv**: The result of the file, 1_Data_Cleaning.Rmd. This is the data used in the analysis. The entire process is documented in the R Markdown file, but methods include condensing columns, creating Likert scales on branching questions, and creating the affective polarization variable. 

- **IV_combos_new.csv**: CSV file provides the factors corresponding to each of the 192 posts. Used in the data cleaning script - 1_Data_Cleaning.Rmd - this was used to go from Qualtrics’ coding of which post a survey-taker was shown to the independent variables that represent that post. 

## Images

- Images folder: Contains 4 pdfs of the conjoint experiment results. These are produced by running 2_Double_Edged_Feed_Analysis.Rmd. Each plot shows the AMCE by political party of the survey respondent across the six independent variables. The 4 plots correspond to the 4 dependent variables (electric vehicle policy preferences, greenhouse emissions policy preferences, affective polarization, and likelihood to interact). 

## Survey

- **Double_Edged_Feed_Full_Survey.pdf**: A full copy of the user survey created in Qualtrics. 


IRB was obtained through Washington University in St. Louis. 

Questions about this paper or repository can be directed to Jean Springsteen at jmspringsteen@wustl.edu. 
