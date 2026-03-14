# Exercise and Student Cognitive Performance

## Project Overview
This project investigates whether physical exercise influences students' perceived cognitive functions and short-term academic productivity.

## Research Questions
- Does exercise frequency influence productivity?
- Do cognitive effects such as increased energy, higher motivation, or reduced stress influence productivity?
- Which exercise types are associated with higher productivity?

## Tools Used
- Google Sheets
- Tableau

## Data Collection
The dataset was collected through a survey targeting students. Respondents were presented with a series of statements regarding the cognitive effects they experience following physical exercise.

Participants evaluated each statement using a 5-point Likert scale:

1 = Strongly Disagree  
2 = Disagree  
3 = Neutral  
4 = Agree  
5 = Strongly Agree  

Statements measured perceived short-term changes in:
- energy levels
- motivation
- stress reduction
- focus
- mood
- academic productivity
- motives for exercising
- overall general impact

In addition, respondents reported their typical:
- exercise frequency
- exercise intensity
- exercise type

This quantitative survey formed part of a **mixed-methods research approach**, where quantitative results were complemented by a qualitative component exploring students' perceptions of exercise and academic performance.

## Data Preparation
Data cleaning and preparation were performed in Google Sheets before importing the dataset into Tableau.

The preparation process included:

- Cleaning and standardizing categorical variables 
- Handling missing values and replacing undefined categories with appropriate labels
- Creating midpoint variables for grouped responses including age group and exercise frequency
- Structuring the dataset into two tables (`clean_data` and `clean_exercise_type`) connected through a respondent identifier

These steps ensured that the dataset could be properly analysed and visualized in Tableau.

## Methodology
The analysis was conducted using interactive dashboards built in Tableau.

The dashboards explore:

- relationships between exercise behaviour and perceived productivity
- correlations between cognitive outcomes (energy, stress reduction, motivation) and productivity
- differences in productivity across exercise types, frequency levels, and intensity

Filters allow the analysis to be segmented by demographic variables such as gender, age group, and degree pursued.

## Dashboards

### Cognitive Effects of Exercise
![Dashboard](dashboard_cognitive_effects.png)

### Exercise Behaviour and Productivity
![Dashboard](dashboard_exercise_productivity.png)

## Tableau Workbook
The packaged Tableau workbook (.twbx) is included in this repository.

## Key Findings
The analysis suggests several patterns in the relationship between exercise and perceived academic productivity:

- Higher exercise frequency is generally associated with higher reported productivity levels.
- Cognitive effects such as increased energy and motivation show strong positive relationships with productivity.
- Reduced stress following exercise also appears to contribute to improved productivity.
- Certain exercise types appear to be associated with higher productivity outcomes, although results vary across respondents.

These findings suggest that physical exercise may play a meaningful role in supporting students’ perceived cognitive performance and short-term academic productivity.
