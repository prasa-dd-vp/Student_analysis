# Student analysis

## Introduction
The aim is to analyse the abilities of the individiual students and the average performance of a class, not just with the CGPA but also with the help of the skills they have developed during the course of studies. The analysis uses python for the wrangling process and R language for exploratory data analysis. The result of the analysis is knitted as an html file which contains the visualizations. 

## Dataset
The dataset which I have used for analysis is a combination of two different datasets. One of the dataset contains all the basic details of the students and their co-curricular activities(skills.csv) and another one contains the CGPA of each student(cgpa.csv). 

## Data Wrangling
The dataset contains many missing categorical values. The type conversions and spelling mistakes have been corrected and extra columns of interesting features have been created. Jupyter notebook environment is used for this purpose. After cleaning process is done, the two different datasets are merged into a single one(student_analysis.csv) by eliminating columns of no interest.

## Exploratory data analysis
The exploratory data analysis is performed on the RStudio. The 'student_analysis.csv' file is used for analysing throughout the process. The visulaizations are created using the package named 'ggplot'. The visulaizations contains univariate and bivariate analysis. After the analysis is completed, the result is knitted as an html file which contains only the visulaizations.
