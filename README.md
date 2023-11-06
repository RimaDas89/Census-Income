# Census-Income
**Project Goal:** To develop a predictive model using the provided dataset to determine whether an individual's income exceeds $50,000 per year, leveraging demographic and socio-economic features to help understand and address income disparities in the US population.
![1_q10a0PIU65qb41wdKaSwoA](https://github.com/RimaDas89/Census-Income/assets/121311261/3711bb7f-a5e3-44ed-a784-5ebc2552da9a)

### Project Description:
This data was extracted from the 1994 Census Bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). The prediction task is to determine whether a person makes over $50K a year.
Description of fnlwgt (final weight)

The weights on the Current Population Survey (CPS) files are controlled to independent estimates of the civilian non-institutional population of the US. These are prepared monthly for us by the Population Division here at the Census Bureau. We use 3 sets of controls. These are:
1.	A single cell estimate of the population 16+ for each state.
2.	Controls for Hispanic Origin by age and sex.
3.	Controls by Race, age and sex.
   
We use all three sets of controls in our weighting program and "rake" through them 6 times so that by the end we come back to all the controls we used. The term estimate refers to population totals derived from CPS by creating "weighted tallies" of any specified socioeconomic characteristics of the population. People with similar demographic characteristics should have similar weights. There is one important caveat to remember about this statement. That is since the CPS sample is actually a collection of 51 state samples, each with its own probability of selection, the statement only applies within the state.

**Dataset Link-**

https://raw.githubusercontent.com/dsrscientist/dataset1/master/census_income.csv
