# ChuangWhiteheadLopez_ENV797_TSA_FinalProject
ERCOT Load Forecast

Run data_pull followed by ts_object_creation before modeling!

ercot_load 2013-06-13 EDT to 2025-04-05 EDT
ercot_fuel_mix 2017-01-01 EST to 2025-04-05 EDT

FINAL REPORT INSTRUCTIONS:

### General Guidelines

1. Use Rmd for your final report.

2. Write in scientific style, not narrative style.

3. [Global options for R chunks](https://rmarkdown.rstudio.com/lesson-3.html) should be set so that only relevant output is displayed. Turn on/off messages and warnings when applicable to avoid unnecessary outputs on the pdf.

4. Make sure your final knitted PDF looks professional. Format tables, figures, chapters, etc.

5. Make sure you add a link to you Github repository in the final report. If you're using public data. Make the repository public. If using private data, make it private and please send me an invitation to collaborate. Otherwise, I will not be able to access your repository.

6. Make sure the PDF file has the file name "Lastname1_Lastname2_Lastname3_ENV797_Project.pdf" and submit it to Sakai under A09 - Final Project - Part III. You will only submit your PDF file. One submission per group.

### Contents of the Report 

#### Introduction, Motivation, Relevance, Objectives

Write a few paragraphs detailing the rationale for your study. This should include both the context of the topic as well as a rationale for your choice of dataset (reason for location, variables, etc.). You may choose to include citations if you like or any other reference you may have used during the project (optional).

#### Dataset information

Provide information on how the dataset for this analysis were collected (source), the data contained in the dataset (format). Describe how you wrangled/processed your dataset to get the time series object.

Add a table that summarizes your data structure (variables, units, ranges and/or central tendencies, data source if multiple are used, etc.). This table should inserted as a `kable` function in an R chunk. Just show the first 10 rows of your data. Do not include the code used to generate your table.


#### Analysis (Methods and Models)

Describe the analysis and tests that were performed. Described the components of the time series you identified. List any packages and functions used. Include visualizations of your dataset (i.e. time series plot, ACF, PACF, etc). 

Format your R chunks so that graphs are displayed but code is not displayed. Accompany these graphs with text sections that describe the visualizations and provide context for further analyses.

Each figure should be accompanied by a caption, and referenced within the text if applicable.

#### Summary and Conclusions

Summarize your major findings from your analyses in a few paragraphs and plots. What conclusions do you draw from your findings? Any insights on how to improve the model?