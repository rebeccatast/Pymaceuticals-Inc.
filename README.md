# Pymaceuticals-Inc.

Pymaceuticals Inc. specializes in anti-cancer drug regimens. Recently, Pymaceuticals began looking for treatments for squamous cell carcinoma (SCC). In this study, 249 mice were identified as having an SCC growth. Each mouse was subjected to one of 10 different drugs of the course of 45 days. Tumor growth was observed, measured, and recorded at equal increments time period of the course of the drug trial. The researchers were particualarly interested in the drug Capomulin in comparison with the drugs in the study. 

This script was built to compare the results of the 10 different drugs and to provide a more indepth analysis of the results produced by the drug Capomulin. Specifically the script completes the following tasks:

- Merged two datasets - MouseData.CSV and StudyResults.csv. The CSV titled "MouseData" contains mouse specific information including Mouse ID, Drug Regimen, Sex, Age, and Weight. The "StudyResults" CSV conains Mouse ID, Timepoints, Tumor Volume, and Metastatic Sites. The two            datasets are merged by "Mouse ID".
      - Cleans the merged dataset to remove any duplicate information. 
      - Generates a summary statistics table showing the mean, median, mode, standard deviation and SEM of the overall tumor volume for each drug regimen. 
      - Generates two identical bar plots (using Pandas and Matplotlib Pyplot) that shows the total number of mice trials for each drug regimen. 
      - Generates two identical pie plots (using Pandas and Matplotlib Pyplot) to show distribution of unique female and male mice in the study. 
      - Calculates the final tumor volume for each mouse for the top four most promising drug regimen: Capomulin, Ramicane, Infubinol, and     Ceftamin. 
      - Calculates the quartiles and IQR for the top four drug regimens and identifies any potential outliers. 
      - Generates a box and whisker plot for final tumor volume for each of the top four drug regimen. 
      - Creates a line plot for one specific mouse in the Capomulin drug trial demonstrating the changes in tumor size over time. 
      - Generates a scatter plot demonstrating the relationship between mouse weight and average tumor volume for the Capomulin drug trial. 
      - Calculates the correlation coefficient and a linear regression model between mosuse weight and average tumor volume for the Capomulin drug trial. 
