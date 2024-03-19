# Analysis of Alcohol Abuse and its Relation to Mental and Physical Health in the United States


## Introduction

This project involves an analysis of data from the CDC'S Behavioral Risk Factor Survey (BRFSS) from 2018. The purpose of this project is to answer these two questions: "What is the extent of alcohol abuse in the United States?", and "How do mental and physical health influence the likelihood of someone engaging in binge drinking?"  Multiple techniques, such as an exploratory data analysis, logistic regression, and data visualization will be utilized to predict the likelihood of individuals engaging in binge drinking based on their mental and physical wellbeing.
 

## Data

The data used in this project comes directly from the CDC's Behavioral Risk Factor Survey [BRFSS](https://www.cdc.gov/brfss/annual_data/annual_2018.html) from 2018.

#### How is Alcohol Abuse Measured?

In this project, I looked at three different measures of alcohol abuse: prevalence, intensity, and frequency.

* **Prevalence**: This refers to the percentage of adults in a given state who have consumed a certain number of alcoholic beverages on at least one occasion in the past 30 days. This can be 4 or more drinks for women, or 5 or more drinks for men.

* **Intensity**: This refers to the maximum number of alcoholic beverages consumed on a single occasion among those who binge drink, in the past 30 days.

* **Frequency**: This refers to the average number of ‘binge drinking’ occasions among those who binge drink, in the past 30 days.

  #### How are Mental and Physical Health Measured?

In this project, I looked at three different measures of alcohol abuse: prevalence, intensity, and frequency.

* Deppressive Disorder (addepev2) : Survey participants are asked the following question: "(Ever told) you have a depressive disorder (including depression, major depression, dysthymia, or minor depression)?" If they answer "No," a value of 0 is assigned. If they answer "Yes," a value of 1 is assigned.

* Poor Mental Health Days (menthlth) : Survey participants are asked the following question: "Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good?”

* Poor Physical Health Days (physhlth) : Survey participants are asked the following question: “Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good?”

* Poor General Health (genhlth) : Survey participants are asked the following question: “Would you say that in general your health is: 1 - Excellent, 2 - Very Good, 3 - Good, 4 - Fair, 5 - Poor, 7 - Don’t Know/Not Sure?”


## Questions to be Answered

* **Where in the United States is Binge Drinking the Most Prevalent?** : Which states/regions of the United States have the highest rates of binge drinking? That is, in which states do the greatest proportion of the state population engage in binge drinking?

* **Where in the United States is Binge Drinking the Most Intense?** : Which states/regions of the United States have the highest mean value for "maximum number of drinks consumed in a single occassion" among those who binge drink?

* **Where in the United States is Binge Drinking the Most Frequent?** : In which states/regions do binge drinkers have the most frequent 'binge drinking occasions?'

* **Do Mental and Physical Health Influence the Likelihood of Someone Engaging in Binge Drinking?** : Are people suffering from poor mental or physical health more or less likely to engage in binge drinking?

