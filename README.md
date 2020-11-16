# Kenya-Demographics-Health-Survey-KDHS--2014
---

> Author: Richard Taracha

> Date: 16/11/2020

![kenya2](https://user-images.githubusercontent.com/67068918/99252543-2cc36700-2820-11eb-92cd-f7356a03c5c3.png)

---

### Table of Contents
Sections headers used to reference locations of each destination:

- [External Data Source Validation](#external-data-source-validation)
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#recommendations)
- [Author Information](#author-information)

---

## External Data Source Validation

The data is originally from the Demographic and Health Surveys Program for the Kenya Demographics Health Survey (KDHS 2014). The data is provided and can be accessed via https://dhsprogram.com/data/dataset/Kenya_Standard-DHS_2014.cfm?flag=0/

> All personally identifying information has been removed from the data.

## Understanding The Context

The Demographic and Health Surveys (DHS) Program has collected, analyzed, and disseminated accurate and representative data on population, health, HIV, and nutrition through more than 400 surveys in over 90 countries.

As a Data professional you are tasked to determine the main factors that can help determine the number of total children ever born by a woman of reproductive age in Kenya. You are provided with the Kenya Demographics Health Survey (KDHS 2014) data set.

#### Technologies and Tools

- Pandas
- Numpy
- Matplotlib
- Seaborn

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Project Deliverable
Deliverable is a Python notebook with my statistical data analysis:

* Notebook name: Statistical Analysis of the Kenya Demographics Health Survey.ipynb

Dataset:
The Demographic and Health Surveys (DHS) Program URL: https://bit.ly/khds_dataset

The variables of interest in the data are:
CASEID: Unique Case identifier
- V010: Respondents Year of Birth
- V012: Respondents current age
- V025: Type of residence
- V024: Region
- V106: The highest level of education
- V152: Age of household head
- V201: Total children ever born

NB: The respondent for the provided data is a woman of a reproductive age

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Recording the Experimental Design
1. Load libraries
2. Load dataset with the following variables:
    * CASEID : Unique Case identifier
    * V010 : Respondents Year of Birth
    * V012 : Respondents current age
    * V025 : Type of residence
    * V024 : Region
    * V106 : Highest level of education
    * V152 : Age of household head
    * V201 : Total children ever born
3. Answer the deliverables outlined below
4. Summarize findings.

Given the dataset, I performed data exploration, data wrangling (cleaning and analysis) and statistical data analysis in an effort to come with a summary of findings: 

**Deliverables:**
* Input the dataset provided and displayed the head(5) of the dataset with the above variables of interest only.
* Calculated the mean, median and mode for V012 , V152 and V201. Would I prefer mean or median for V201?
* Calculated the Range, IQR and standard deviation for V012 and V152. Commented on the variability of the variables.
* Ploted a histogram of V012 and V152 and explained the skewness.
* Created a frequency table for V024 and V106 then plotted a barchart for the two variables.
* Created a boxplot of V201 by (V025, V106, V024) separately.
* Created a scatter plot and computed the Pearson Correlation Coefficient between V201 and V012 explaining my findings.


[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Summary Of Findings

- From my analysis, most of the delays were caused by late returns from field trips
- Heavy traffic and mechanical problems are the most frequent reasons for bus delays.
- G.V.C., LTD, LEESEL TRANSPORTATION CORP (B2192) and PIONEER TRANSPORTATION CO	are the bus companies with the highest number of breakdowns.
- There were a total number of 58329 students on the bus when it broke down and a total number of 890829 on the bus when it was running late.

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Recommendations

From the above analysis, below are our recommendations:

* Since most of the delays were caused by Late return from Field Trips, it is recommended that the buses be rotated out to prevent breakdown i.e the buses going out for field trips should be on rotational basis.

* Heavy traffic is the most frequent reason for running late and hence either the roads be expanded to ease traffic or the number of vehicles plying that route should be regulated. Alternative routes may also be considered.

* An investigation into LITTLE RICHIE BUS SERVICE which is the bus company with the most breakdowns should be launched to understand the reason.

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)


