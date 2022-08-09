# Project 1
Project 1 Group 1

# Introduction

Project time for the cohort in the Data Analysis and Visualization bootcamp. Broken up into groups, we take everything we learned in the first seven weeks, from Pandas to Matplotlib, and try our hand at telling a story with data. With an open-ended assignment, our group searched almost aimlessly through the interwebs, until we happened upon from an experimental data system called the Household Pulse survey. In phases, it was survey conducted during the coronavirus pandemic and conducted by the National Center for Health Statistics partnered with the Census Bureau to provide information about the impact of the pandemic.

Included in the online survey were questions to obtain information on the frequency of anxiety and depression, which will be our focus tonight. For comparison, in 2019 10.8% of adults aged 18 and over reported symptoms of anxiety disorder or depressive disorder. At its peak in November 2020, the national estimate was around 42.6%. Tonight, we’ll check on in Americans, looking through the magnifying glass at age groups, education, gender, as well as sexual orientation. Then we will move the lens onto vaccination rates and state lines to identify any trends.

The CDC was kind enough to let us borrow their [data](https://www.cdc.gov/nchs/covid19/pulse/mental-health.htm) and so our story begins much like every other data scientists in the world: some light data wrangling and data cleaning. In this repository, there are two Jupyter notebooks: Data Cleaning and Mental Health in America. In the Data Cleaning notebook, you will find the usual grouping, sorting, filtering with loc and iloc, a merge here and there, just some cleaning to fit our purposes of the various analytical lenses we take. The Mental Health in America notebook follows a presentation layout, figures and graphs are displayed in order of how they will be presented. There is a resources folder with original datasets as well as CSV files exported by the Data Cleaning notebook for later use.

This project is an exercise in coding as well as data analysis. We look at mental health through the lenses of age, education, sexual gender as well as sexual orientation. Then we try to find out if vaccination rates or a state's political leaning affects the mental health of American citizens.


# Visuals and Analysis

Age Group Line Graph

https://github.com/nitchon/project1/blob/main/output_data/line_all_By_Age.png

Based on the data collected from April 2020 to July 2022 , the younger age group of 18-29 years old has highest average depression rate vs the older age group of 70-79 years old and 80 years old. All age groups have the same peak of depression rate occurring in Sept 2020 to Mar 2021. Similar decline in rate of depression for all age groups occurs in May 2021 and no significant increase until the end of the June 2022.

Education Line Graph

https://github.com/nitchon/project1/blob/main/output_data/line_all_By_Education.png

Based on the graph, people with “less than high school diploma” have the highest average depression rate.  

Sexual Orientation Line Graph

![image](https://user-images.githubusercontent.com/107419765/183315536-6185716c-b0f7-4efa-89d9-c7317bb82ae8.png)

Based on the graphed data, straight people are considerably less depressed than bisexual or gay/lesbian people.  Bisexual people have the highest rate of depression symptoms.  Due to "bi-erasure" concept, bisexual people are considered "afriad to come out" and not as welcomed to the LGBTQ community due to this bias like gay or lesbian people are. Bisexual people are also least likely to come "out" to friends and participate in Pride events because of this bias. This information comes from research regarding this topic, and does not reflect my thoughts/opinion. (https://www.psychologytoday.com/us/blog/women-who-stray/201904/why-are-mental-health-issues-greater-among-bisexual-people)

Sexual Gender Line Graph

![image](https://user-images.githubusercontent.com/107419765/183315547-b1a0a40f-3cae-4bc3-8661-856223c0dbac.png)

Based on the graphed data, women have a higher percentage of depression symptoms. This is an example of sampling bias, since research shows men will most likely not express feelings of depression as easily as women do. Another potential sampling bias is if women or men are more likely to answer a phone survey.  (https://www.psychologytoday.com/us/blog/pop-psych/201607/why-women-are-more-depressed-men)

Vax Rate vs Mental Wellbeing in Select States

![image](https://user-images.githubusercontent.com/nitchon/project1/main/Vax_rate_by_state.png)

Percentages of anxiety and depression decrease as a state vax rate increase. 
The increase in mental health distress was shown early in the pandemic through the pulse 
dataset, however the increase in vaccination rate is simply a function of time. Other factors could
have as easily improved mental health as well up to and including that the populace simply 
became inured to concerns over Covid-19. However by in large there is a decrease over this time 
period and the populace becoming more vaccinated likely played a role in easing overall concern
of the pandemic as well as allowing for an easing of restrictions that could have also been 
negatively affecting mental health outcomes.


Political Affiliation with Depression & Anxiety

**insert image**

Based on the graph, the red states (Republican) appear to be higher, but there is no meaningful/conclusive evidence that a state’s political affiliation affects the states' percentage of exhibiting symptoms. When graphed in bar or line form, red and blue states appear to mirror each other. After analyzing a state’s health professional shortage areas in relation to mental health, the scatter plots show no correlation. This shows how mental health is discussed asa society.

# Modules Used
    - Pandas
    - Matplotlib
    - Numpy
    - Scipy

# Conclusions
Younger age groups reported in higher percentages of anxiety and depression disorder symptoms. People with less than a high school diploma reported higher percentages of the aformentioned symptoms. Females trended higher than males through the pandemic. People who identified as straight trender lower than the Bisexual and Gay or Lesbian identifications. As a state's vaccination rate increases, the percentage of respondents to the Household Pulse survey seems to decrease over time. At a glance, red states may report higher rates of symptoms of anxiety or depression, but nothing conclusive. It is more appropriate to say that depression and anxiety affects everyone regardless of political party. A mental health survey with a question denoting political party would be better suited to tackle this analysis.

