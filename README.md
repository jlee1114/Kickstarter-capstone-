# Insight into successes of kickstarter campaigns
This project is a part of the Data Science Immersive at Galvanize San Francisco. 

#### -- Project Status: [Active]

## Project Intro/Objective
Kickstarter is a funding platform for creative projects. Everything from films, games, and music to art, design, and technology.
The project owner gets up to 60 days to meet its funding goal. Crowdfunding is an alternative form of financing that is rapidly gaining popularity.

This project aims to explore and see what kind of trends or features contribute to the success of kickstarter projects.

### Methods Used
* Inferential Statistics
* Exploratory Data Analysis
* Data Visualization
* Hypothesis Testing

### Technologies
* Python
* Spark
* Sparksql
* Pandas, Numpy, jupyter

## Project Description
This dataset has been taken from webrobots.io which is a battle tested web crawler platform that collects tens of millions data points daily.
The dataset is taken from April 2009 up to December 2020 which contained all the information from 2009 to 2020.
https://webrobots.io/kickstarter-datasets/ 
The main questions that I am interested in answering are:
* What insights can we discover about Kickstarter projects up until now? 
* What roles play a factor to having a successful project?

The first step was to clean the raw data. Since the data is raw as it gets, it is not cleaned at all with 217,213 entries and 50+ features for each entry. The dataset comes in at about 2.27Gbs.
The preprocessed data will only have the features that I am interested in analyzing and I will only be analyzing projects from the US. 

I decided to conduct an exploratory analysis of these projects. This included looking at categories, goal/pledged amount, and duration based on their success rate and failure rate. The dataset included these following features:

| Columns           |     |
| :---              |--- |
| id                     | 
| name                   | 
| country                |
| backers_count          |
| currency               | 
| deadline               | 
| goal                   | 
| launched_at            | 
| pledged                | 
| category               |
| sub_category           |
| spotlight              |
| duration               |
| fr                     |




## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
