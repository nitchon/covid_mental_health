# project1
Project 1 Group 1

# Description

Project time for the cohort in the Data Analysis and Visualization bootcamp. Broken up into groups, we take everything we learned in the first seven weeks, from Pandas to Matplotlib, and try our hand at telling a story with data. With an open-ended assignment, our group searched almost aimlessly through the interwebs, until we happened upon from an experimental data system called the Household Pulse survey. In phases, it was survey conducted during the coronavirus pandemic and conducted by the National Center for Health Statistics partnered with the Census Bureau to provide information about the impact of the pandemic.

Included in the online survey were questions to obtain information on the frequency of anxiety and depression, which will be our focus tonight. For comparison, in 2019 10.8% of adults aged 18 and over reported symptoms of anxiety disorder or depressive disorder. At its peak in November 2020, the national estimate was around 42.6%. Tonight, we’ll check on in Americans, looking through the magnifying glass at age groups, education, gender, as well as sexual orientation. Then we will move the lens onto vaccination rates and state lines to identify any trends.

The CDC was kind enough to let us borrow their [data](https://www.cdc.gov/nchs/covid19/pulse/mental-health.htm) and so our story begins much like every other data scientists in the world: some light data wrangling and data cleaning. In this repository, there are two Jupyter notebooks: Data Cleaning and Mental Health in America. In the Data Cleaning notebook, you will find the usual grouping, sorting, filtering with loc and iloc, a merge here and there, just some cleaning to fit our purposes of the various analytical lenses we take. The Mental Health in America notebook follows a presentation layout, figures and graphs are displayed in order of how they will be presented. There is a resources folder with original datasets as well as CSV files exported by the Data Cleaning notebook for later use.

This project is an exercise in coding as well as data analysis. We look at mental health through the lenses of age, education, sexual gender as well as sexual orientation. Then we try to find out if vaccination rates or a state's political leaning affects the mental health of American citizens.


# Visuals


# Modules
    - Pandas
    - Matplotlib
    - Numpy
    - Scipy

# Conclusions
Younger age groups reported in higher percentages of anxiety and depression disorder symptoms. People with less than a high school diploma reported higher percentages of the aformentioned symptoms. Females trended higher than males through the pandemic. People who identified as straight trender lower than the Bisexual and Gay or Lesbian identifications. As a state's vaccination rate increases, the percentage of respondents to the Household Pulse survey seems to decrease over time. At a glance, red states may report higher rates of symptoms of anxiety or depression, but nothing conclusive. It is more appropriate to say that depression and anxiety affects everyone regardless of political party. A mental health survey with a question denoting political party would be better suited to tackle this analysis.