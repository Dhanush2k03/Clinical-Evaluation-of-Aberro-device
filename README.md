Clinical Data Analysis of 3nethra Aberro Handheld Auto Refractometer
Project Overview
This project involves a comprehensive clinical data analysis of the 3nethra Aberro Handheld Auto Refractometer. The aim is to compare the device's measurements with the gold standard of subjective refraction, and assess the accuracy and reliability of the Aberro device in a clinical setting.

The project includes data cleaning, preprocessing, statistical analysis, hypothesis testing, and visualization techniques to draw insights from the collected dataset.

Dataset Description
Data Collected: Around 9,000 entries from both the Aberro device and subjective refraction.
Parameters: Spherical (SPH), Cylindrical (CLY), Axis, SPE, J0, J45, and more.
Project Files
MY_FINAL.ipynb:

Data cleaning and preprocessing.
Removal of outliers beyond the device range (>14) and based on z-scores.
Calculation of mean, standard deviation, and empirical rule checks.
MY_FINAL_2.ipynb:

Population mean calculation.
Sampling with replacement and generating sample means over 10,000 iterations.
Calculation of standard error and visualization through histograms and normal curves.
MY_FINAL_3.ipynb:

Parameter-wise data count analysis.
Plotting of boxplots to identify distributions and outliers.
MY_FINAL_VECTOR.ipynb:

Import of cleaned data from Excel for further analysis.
Vector notation calculations for SPE, J0, and J45.
Cross-verification using z-values, plotting of boxplots, hypothesis testing, and Bland-Altman analysis.
Statistical analysis including correlation plots, percentage calculations, and t-tests.
Statistical Techniques and Visualizations
Data cleaning using z-scores and device-specific thresholds.
Sampling techniques to estimate population mean and standard error.
Empirical rule checks for data consistency.
Hypothesis testing to validate findings.
Bland-Altman plots for comparison between Aberro and subjective refraction.
Correlation plots, percentage calculations, and boxplots for visualizing results.
Key Findings
The detailed statistical analysis and visualizations provide insights into the accuracy and reliability of the Aberro device when compared to the gold standard subjective refraction.

Accessing the Code
To explore the project code and detailed analysis, you can access the Jupyter notebooks in this repository. Each file includes inline comments explaining the workflow, calculations, and visualizations.
