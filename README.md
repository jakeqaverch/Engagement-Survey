# Engagement Survey
# Data Overview

![image](https://github.com/jakeqaverch/Engagement-Survey/assets/170358772/82f4f68e-d4a9-4f6f-a582-ce2009746b28)

- The dataset has 27 columns and 1000 entries.
- 6 of the columns are identifers and 20 of the columns are engagment questions
- Each columns data type is identified. 
- Every column has 1000 non - null values, indicating no missing data.
  
| Gender | Count | Proportion |
|--------|-------|------------|
| Male   | 510   | 0.51       |
| Female | 490   | 0.49       |

| Race             | Count | Proportion |
|------------------|-------|------------|
| Caucasian        | 543   | 0.543      |
| Asian            | 228   | 0.228      |
| Hispanic         | 96    | 0.096      |
| African American | 90    | 0.090      |
| Other            | 43    | 0.043      |

| Department               | Count | Proportion |
|--------------------------|-------|------------|
| Support                  | 96    | 0.096      |
| Product Management       | 94    | 0.094      |
| Sales                    | 94    | 0.094      |
| Services                 | 90    | 0.090      |
| Engineering              | 88    | 0.088      |
| Legal                    | 84    | 0.084      |
| Marketing                | 82    | 0.082      |
| Business Development     | 81    | 0.081      |
| Accounting               | 75    | 0.075      |
| Human Resources          | 73    | 0.073      |
| Training                 | 72    | 0.072      |
| Research and Development | 71    | 0.071      |

| Race             | Count | Proportion |
|------------------|-------|------------|
| Entry Level        | 424          | 0.424      |
| Junior            | 360   | 0.360      |
| Mid-Level         | 126           | 0.126      |
| Senior | 59    | 0.059      |
| Executive            | 31    | 0.031      |

- Gender distribution is balanced
- Majority of the individuals are Caucasian (54.3% of the dataset), followed by Asians (22.8%)
- Significant portion of the workforce is at the Entry Level (42.4%) and Junior level (36%), indicating a young or early-career workforce. Senior levels make up a smaller fraction, which is typical as organizational pyramids narrow at the top

# Individual Question Analysis

## On a scale of 0 to 10, how likely is it that you would recommend DataSkillUp as a place to work? (eNPS)     
### Base Counts
| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 14    | 0.014      |
| 2      | 8     | 0.008      |
| 3      | 25    | 0.025      |
| 4      | 45    | 0.045      |
| 5      | 75    | 0.075      |
| 6      | 146   | 0.146      |
| 7      | 205   | 0.205      |
| 8      | 208   | 0.208      |
| 9      | 162   | 0.162      |
| 10     | 112   | 0.112      |
| Mean ||7.213|
| Std ||1.944

### Converting to eNPS measures
| eNPS category   |   count |
|:----------------|--------:|
| Passive         |     413 |
| Detractor       |     313 |
| Promoter        |     274 |




- The sentiment on this question is relatively positive with 83.3% of respondents answering with a 6 or greater and a mean of 7.213.

## Overall, I am satisfied with my experience working at DataSkillUp

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 13    | 0.013      |
| 3      | 389   | 0.389      |
| 4      | 555   | 0.555      |
| 5      | 43    | 0.043      |
| % Positive || 59.8           |

- The sentiment on this question is relatively mixed with 59.8% of respondents answering positively.
- The 13% who answered with a 2 warrent further investigation.

## I can see that senior leaders (Directors+) in my org value people’s differences.         

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 13    | 0.013      |
| 2      | 62    | 0.062      |
| 3      | 201   | 0.201      |
| 4      | 420   | 0.420      |
| 5      | 304   | 0.304      |
| % Positive || 72.4           |

- The sentiment on this question is relatively positive with 72.4% of respondents answering positively.

## The executive leadership team (SVP+) keeps me informed about what is happening at DataSkillUp     

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 14    | 0.014      |
| 3      | 378   | 0.378      |
| 4      | 557   | 0.557      |
| 5      | 51    | 0.051      |
| % Positive || 60.8           |

- The sentiment on this question is relatively mixed with 60.8% of respondents answering positively.
- It is a positive sign that no one answered with a 1.

## I believe in DataSkillUp's ambitions as a company.    

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 0     | 0          |
| 3      | 54    | 0.054      |
| 4      | 627   | 0.627      |
| 5      | 319   | 0.319      |
| % Positive || 94.6          |

- The sentiment on this question is relatively positive with 94.6% of respondents answering positively.
- All respondants answered with a 3+ which is very positive.

## I trust DataSkillUp's senior leaders (Directors+).      

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 4     | 0.004      |
| 3      | 190   | 0.190      |
| 4      | 586   | 0.586      |
| 5      | 220   | 0.220      |
| % Positive || 80.6          |

- The sentiment on this question is relatively positive with 80.6% of respondents answering positively.

## I believe my manager genuinely cares about me and my wellbeing. 

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 0     | 0          |
| 3      | 0     | 0          |
| 4      | 367   | 0.367      |
| 5      | 633   | 0.633      |
| % Positive || 100          |

- The sentiment on this question is positive with 100% of respondents answering positively.
- This is a very good sign for overall manager support.

## I feel recognized for my contributions.  

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 13    | 0.013      |
| 3      | 389   | 0.389      |
| 4      | 555   | 0.555      |
| 5      | 43    | 0.043      |
| % Positive || 80.2         |

- The sentiment on this question is positive with 80.2% of respondents answering positively.

## I can come to work without feeling the need to hide a part of who I am.  

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 1     | 0.001      |
| 2      | 47    | 0.047      |
| 3      | 308   | 0.308      |
| 4      | 491   | 0.491      |
| 5      | 153   | 0.153      |
| % Positive || 64.4         |

- The sentiment on this question is relatively mixed with 64.4% of respondents answering positively.
-This 1 outlier should be examined further as they may feel marginalized within their group.

## I have a good working relationship with members of my team.   

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 1     | 0.001      |
| 3      | 55    | 0.055      |
| 4      | 600   | 0.600      |
| 5      | 344   | 0.344      |
| % Positive || 94.4          |

- The sentiment on this question is positive with 94.4% of respondents answering positively.
- The outlier who answered 2 should be examined further as they may need to change teams.

## My manager gives me the autonomy I need to do my best work.    

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 6     | 0.006      |
| 3      | 202   | 0.202      |
| 4      | 619   | 0.619      |
| 5      | 173   | 0.173      |
| % Positive || 79.2          |

- The sentiment on this question is positive with 79.2% of respondents answering positively.
- The outliers who answered 2 should be examined further as they may need to change managers.

## My manager gives me the opportunity to try new things that align with my career goals. 

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 11    | 0.011      |
| 3      | 288   | 0.288      |
| 4      | 610   | 0.610      |
| 5      | 91    | 0.091      |
| % Positive || 70.1          |

- The sentiment on this question is relatively positive with 70.1% of respondents answering positively.
- The outliers who answered 2 should be examined further.

## My manager creates an environment where I can safely learn from my mistakes. 

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 52    | 0.052      |
| 3      | 335   | 0.335      |
| 4      | 466   | 0.466      |
| 5      | 147   | 0.147      |
| % Positive || 61.3          |

- The sentiment on this question is relatively mixed with 61.3% of respondents answering positively.

## I believe action will take place as a result of this survey.   

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 23    | 0.023      |
| 2      | 154   | 0.154      |
| 3      | 338   | 0.338      |
| 4      | 323   | 0.323      |
| 5      | 162   | 0.162      |
| % Positive || 48.5          |

- The sentiment on this question is relatively negative with 48.5% of respondents answering positively.
- This should be examined further based on results from previous surveys

## I know what I need to do to be successful in my role.   

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 5     | 0.005      |  
| 3      | 336   | 0.336      |
| 4      | 609   | 0.609      |
| 5      | 50    | 0.050      |
| % Positive || 65.9          |

- The sentiment on this question is relatively mixed with 65.9% of respondents answering positively.
- The outliers who answered 2 should be examined further as they may need more support

## I believe that my skills are well utilized in my role.	  

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 1     | 0.001       |
| 2      | 47    | 0.047      |
| 3      | 601   | 0.601      |
| 4      | 345   | 0.345      |
| 5      | 6     | 0.006      |
| % Positive || 35.1          |

- The sentiment on this question is relatively negative with 35.1% of respondents answering positively.
-This 1 outlier should be examined further.

## I receive regular, actionable feedback throughout the year.

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 0     | 0          |
| 3      | 54    | 0.054      |
| 4      | 602   | 0.602      |
| 5      | 344   | 0.344      |
| % Positive || 94.6          |

- The sentiment on this question is relatively positive with 94.6% of respondents answering positively.

## I believe that my current role is well aligned with my career goals.  

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 88    | 0.088      |
| 3      | 613   | 0.613      |
| 4      | 296   | 0.296      |
| 5      | 3     | 0.003      |
| % Positive || 29.9          |

- The sentiment on this question is relatively negative with 29.9% of respondents answering positively.

## I am able to disconnect from job-related stress after I've completed a typical workday.

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 64    | 0.64      |
| 2      | 221   | 0.221     |
| 3      | 381   | 0.381     |
| 4      | 264   | 0.264     |
| 5      | 70    | 0.070     |
| % Positive || 33.4         |

- The sentiment on this question is relatively negative with 33.4% of respondents answering positively.

## Generally, I believe my workload is reasonable for my role.	

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 102   | 0.102      |
| 2      | 311   | 0.311      |
| 3      | 365   | 0.365      |
| 4      | 167   | 0.167      |
| 5      | 55    | 0.055      |
| % Positive || 22.2         |

- The sentiment on this question is relatively negative with 22.2% of respondents answering positively.
- There were a large number 1 answers here indicated low work life balance but we will examine that further later.

## I have enough flexibility to meet the needs of my personal life.	

| Number | Count | Proportion |
|--------|-------|------------|
| 1      | 0     | 0          |
| 2      | 67    | 0.067      |
| 3      | 588   | 0.588      |
| 4      | 337   | 0.337      |
| 5      | 8     | 0.008      |
| % Positive || 34.5          |

- The sentiment on this question is relatively negative with 34.5% of respondents answering positively.

# Metric Analysis

## Satisfaction
- Combined metric of all questions measuring employees overal satisfaction.
- Maximum value of 20
- A mean of 12.81 which we will examine by groups later.
- A 25th percentile of 11 is negative and should be examined further.
  
| Metric | Value  |
|--------|--------|
| Mean   | 12.819 |
| Std    | 2.275  |
| Min    | 4      |
| 25%    | 11     |
| 50%    |13      |
| 75%    | 14     |
| Max    | 19     |

## Work Life Balance
- Combined metric of the questions dealing with work life balance.
- Maximum value of 3.
- The mean and varience is low which should be examined further.
- Those with low scores should be examined further
  
| Metric | Value  |
|--------|--------|
| Mean   | 0.901 |
| Std    | 0.751 |
| Min    | 0      |
| 25%    | 0     |
| 50%    | 1      |
| 75%    | 1     |
| Max    | 3     |

## Leadership Support
- Combined metric of the questions dealing with support of senior leadership.
- Maxiumum value of 5
- Relatively high mean with lower varience which means people generally support the leadership in the organization.

| Metric | Value  |
|--------|--------|
| Mean   | 4.084 |
| Std    | .84 |
| Min    | 1      |
| 25%    | 4     |
| 50%    | 4      |
| 75%    | 5     |
| Max    | 5     |

## Manager Support

- Combined metric of the questions dealing with support of individual managers.
- Maximum value of 5
- Relatively high mean with lower varience which means people generally have positive experiences with their direct managers.
- Those with low answers should be examined further. If they share similar managers then this should be examined further.

| Metric | Value  |
|--------|--------|
| Mean   | 4.052 |
| Std    | .882 |
| Min    | 1      |
| 25%    | 4     |
| 50%    | 4      |
| 75%    | 5     |
| Max    | 5     |

## Inclusion

- Combined metric of the questions dealing with inclusion.
- Maximum value of 2
- Mean is relatively high but higher varience we will explore this by groups later

|   Metric    |   Value |
|:------|------------:|
| count | 1000        |
| mean  |    1.368    |
| std   |    0.726019 |
| min   |    0        |
| 25%   |    1        |
| 50%   |    2        |
| 75%   |    2        |
| max   |    2        |

## Role Alignment

- Combined metric of the questions dealing with role alignment.
- Maximum value of 3
- Mean is relatively high but higher varience we will explore this by groups later

|  Metric     |   Value |
|:------|----------------:|
| count |     1000        |
| mean  |        1.309    |
| std   |        0.784943 |
| min   |        0        |
| 25%   |        1        |
| 50%   |        1        |
| 75%   |        2        |
| max   |        3        |

# Question + Metric Analysis by Groups
## Gender 
### % Positivity
| Gender | Q1  | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 | Q11 | Q12 | Q13 | Q14 | Q15 | Q16 | Q17 | Q18 | Q19 | Q20 |
|--------|-----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Male   |70.39|80.19|70.78|94.89|86.47|100|86.07|73.72|94.28|65.10|87.25|73.52| 50.00  |66.66|38.03|94.31|24.90|31.76|20.78|49.60|
| Female |48.77|64.28|50.40|94.31|74.48|100|74.08|54.69|94.50|92.74|52.24|48.57|  46.93 |65.10|32.04|94.89|35.10|35.10|23.67|18.77|

- There are signifcant differnece on many questions between male and female employees where females tend to score lower.
- These should be examined further.

### eNPS
| Gender | Mean | Std |
|--------|------|-----|
| Male   7.40|2.02|
| Female 7.01|1.83|

| Gender   |      eNPS score |
|:---------|-----------:|
| Female   | -0.15102   |
| Male     |  0.0686275 |

- Men have a much higher eNPS score

### Metrics

| Gender   |   Satisfaction Mean |   Satisfaction Std |   Wlb Mean |   Wlb Std |   Leadership Support Mean |   Leadership Support Std |   Manager Support Mean |   Nanager Support Std |   Inclusion Mean |   Inclusion Std |   Role Alignment Mean |  Role Alignment Std |
|:---------|--------------------:|-------------------:|-----------:|----------:|-------------------------:|------------------------:|----------------------:|---------------------:|-----------------:|----------------:|---------------------:|--------------------:|
| Female   |               11.73 |               2    |       0.78 |      0.72 |                     3.84 |                    0.83 |                  3.61 |                 0.87 |             1.19 |            0.71 |                 1.32 |                0.79 |
| Male     |               13.86 |               2.03 |       1.02 |      0.76 |                     4.32 |                    0.79 |                  4.48 |                 0.65 |             1.54 |            0.7  |                 1.3  |                0.78 |

- Men have a higher overall satisfaction score but with slightly higher varience
- Men have a higher work life balance score with similar vairence
- Men support the leadership team slightly more with similar varience
- Men have much more support from their manager with lower varience which should be examined further.
- Women feel less included than men
- Values are similar for role alignment

## Race
### % Positivity
| Race               | Q1  | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 | Q11 | Q12 | Q13 | Q14 | Q15 | Q16 | Q17 | Q18 | Q19 | Q20 |
|--------------------|-----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| African-American   |63.33|53.33|72.22|97.77|55.55|100|52.22|5.55|97.77|78.88|71.11|12.22|47.77|76.66|33.33|90.00|24.44|32.22|15.55|31.11|
| Asian              |57.45|78.07|56.57|94.73|91.22|100|89.47|75.43|90.78|75.87|67.54|72.80|43.85|63.59|35.08|96.49|31.57|32.89|27.19|31.57|
| Caucasian          |60.77|79.92|60.40|93.55|88.39|100|86.74|80.29|95.21|80.29|71.08|76.05|49.17|65.00|34.25|94.29|29.65|34.069|21.73|35.17|
| Hispanic           |58.33|43.75|63.54|96.87|52.08|100|59.37|16.66|93.75|83.33|72.91|13.54|53.12|67.70|38.54|94.7| 30.20|35.41|20.83|38.54|
| Other              |55.81|51.16|58.13|95.34|41.86|100|53.48|13.95|97.67|74.41|62.79|23.25|55.81|62.7|41.86|97.67|34.88|25.58|18.60|39.53|

- There is significant differences between employees based on race for many questions. These should be examined further.
- We will examine this further with each metric

### eNPS
| Race               | Mean | Std |
|--------------------|------|-----|
| African-American   |6.90|2.63|
| Asian              |6.49|1.81|
| Caucasian          |7.76|1.36|
| Hispanic           |6.30|2.73|
| Other              |6.79|2.73|

| Race             |          eNPS Score |
|:-----------------|-----------:|
| African American | -0.1       |
| Asian            | -0.355263  |
| Caucasian        |  0.139963  |
| Hispanic         | -0.229167  |
| Other            | -0.0697674 |

- Caucasian employees scored higher on this hispanic and Asian employees scores the lowest score.

### Metrics
| Race             |   Satisfaction Mean |   Satisfaction Std |   Wlb Mean |   Wlb Std |   Leadership Support Mean |   Leadership Support Std |   Manager Support Mean |   Nanager Support Std |   Inclusion Mean |   Inclusion Std |   Role Alignment Mean |  Role Alignment Std |
|:-----------------|--------------------:|-------------------:|-----------:|----------:|-------------------------:|------------------------:|----------------------:|---------------------:|-----------------:|----------------:|---------------------:|--------------------:|
| African American |               11.21 |               1.9  |       0.79 |      0.68 |                     3.79 |                    0.88 |                  3.52 |                 0.8  |             0.69 |            0.61 |                 1.34 |                0.77 |
| Asian            |               13.12 |               1.89 |       0.92 |      0.73 |                     4.21 |                    0.69 |                  4.13 |                 0.8  |             1.54 |            0.61 |                 1.3  |                0.77 |
| Caucasian        |               13.36 |               2.24 |       0.91 |      0.76 |                     4.22 |                    0.81 |                  4.22 |                 0.89 |             1.6  |            0.61 |                 1.29 |                0.8  |
| Hispanic         |               11.33 |               2.08 |       0.95 |      0.8  |                     3.56 |                    0.88 |                  3.65 |                 0.78 |             0.6  |            0.59 |                 1.36 |                0.76 |
| Other            |               11.05 |               1.89 |       0.84 |      0.81 |                     3.47 |                    0.85 |                  3.58 |                 0.7  |             0.65 |            0.61 |                 1.4  |                0.82 |

- African American, Hispanic, and Other employees scored lower on overall satisfaction.
- African American employees scores lower than other emmployees in terms of work life balance with lower varience. This should be examined further.
- Hispanic, Other, and African American employees support the senior leadership the least.
- African American, Hispanic, and Other employees scored lower on manager support which should be examined further.
- African American, Hispanic, and other employees feel less included than other groups
- Values are similar for role alignment

## Level 
### % Positivity
| Level               | Q1  | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 | Q11 | Q12 | Q13 | Q14 | Q15 | Q16 | Q17 | Q18 | Q19 | Q20 |
|--------------------|-----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Entry-Level   |57.31|75.23|58.96|96.22|79.48|100|79.95|64.38|93.63|77.35|72.16|61.32|50.70|65.33|34.90|93.39|29.24|34.66|19.10|35.84|
| Junior        |61.66|68.05|63.33|93.33|82.22|100|79.44|64.16|94.44|82.2A|67.22|58.88|46.94|64.72|33.61|95.00|30.00|30.83|19.35|35.55|
| Mid-Level     |61.11|72.22|65.07|92.85|73.80|100|80.15|62.69|94.44|76.19|66.66|65.87|47.61|61.90|38.88|94.44|34.92|35.71|30.95|25.39|
| Senior        |61.01|72.88|52.54|93.22|86.44|100|83.05|64.40|96.61|77.96|76.27|64.40|37.28|77.96|38.98|98.30|25.42|40.67|23.72|40.67|
| Executive     |64.51|83.87|54.83|96.77|93.54|100|87.09|74.19|100.0|83.87|77.41|64.51|41.93|80.65|32.25|100.0|25.80|69.16|19.35|29.03|

- There is significant differences between employees based on level for many questions. These should be examined further.
- We will examine this further with each metric
  
### eNPS
| Level               | Mean | Std |
|--------------------|-------|------|
| Entry-Level   |7.14|1.97|
| Junior        |7.12|1.99|
| Mid-Level     |7.50|1.75|
| Senior        |7.23|1.91|
| Executive     |7.96|1.58|

| Level       |    eNPS Score |
|:------------|-----------:|
| Entry Level | -0.0660377 |
| Junior      | -0.0666667 |
| Mid-Level   |  0.047619  |
| Senior      |  0.0169492 |
| Executive   |  0.193548  |

- Entry level and junior employees recommend the organization the least. Surprisingly Senior employees scored lower on this. This should be examined further.


### Metrics
| Level             |   Satisfaction Mean |   Satisfaction Std |   Wlb Mean |   Wlb Std |   Leadership Support Mean |   Leadership Support Std |   Manager Support Mean |   Nanager Support Std |   Inclusion Mean |   Inclusion Std |   Role Alignment Mean |  Role Alignment Std |
|:------------|--------------------:|-------------------:|-----------:|----------:|-------------------------:|------------------------:|----------------------:|---------------------:|-----------------:|----------------:|---------------------:|--------------------:|
| Entry Level |               12.79 |               2.2  |       0.9  |      0.77 |                     4.1  |                    0.82 |                  4.04 |                 0.86 |             1.4  |            0.7  |                 1.29 |                0.75 |
| Junior      |               12.74 |               2.26 |       0.89 |      0.73 |                     4.07 |                    0.87 |                  4.03 |                 0.88 |             1.32 |            0.73 |                 1.28 |                0.82 |
| Mid-Level   |               12.86 |               2.37 |       0.92 |      0.73 |                     4.04 |                    0.87 |                  4.03 |                 0.97 |             1.35 |            0.75 |                 1.36 |                0.8  |
| Senior      |               13.12 |               2.51 |       1.05 |      0.86 |                     4.05 |                    0.75 |                  4.17 |                 0.85 |             1.37 |            0.76 |                 1.42 |                0.77 |
| Executive   |               13.32 |               2.69 |       0.71 |      0.59 |                     4.29 |                    0.82 |                  4.26 |                 0.86 |             1.58 |            0.76 |                 1.39 |                0.8  |

- Satisfaction tends to go up with level
- Executive employees scored the lowest on work-life balance which is unsurprising but entry level and junior employees scored low as well
- Senior Leadership support is consistant except for the Executive leadership team which is unsurprising
- Manager support is consistant except for the Executive leadership team which is unsurprising
- Values are similar but Executives are high end outliers
- Role alignment for more entry level employees is lower

## Department
### % Positivity

| Dept               | Q1  | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 | Q11 | Q12 | Q13 | Q14 | Q15 | Q16 | Q17 | Q18 | Q19 | Q20 |
|--------------------|-----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Accounting              |58.66|81.33|58.66|94.66|84.00|100|80.00|61.33|93.33|74.66|76.00|66.66|50.66|68.00|30.66|86.66|33.33|30.86|24.00|40.00
| Business Development    |58.02|67.90|60.49|92.59|86.41|100|81.48|61.72|93.82|85.18|77.77|58.02|41.97|65.43|28.39|100.0|29.62|30.86|23.45|37.03
| Engineering             |63.63|71.59|57.95|94.31|78.40|100|82.95|67.04|93.18|87.50|69.31|61.36|44.31|67.04|38.63|97.72|34.09|42.04|23.86|27.27
| Human Resources         |63.01|76.71|60.27|90.41|80.82|100|69.86|58.90|97.26|73.97|65.75|61.64|50.68|54.79|39.72|95.89|23.28|30.13|12.32|43.83
| Legal                   |54.76|77.38|63.09|93.04|88.09|100|86.90|65.47|91.66|82.14|76.19|65.47|48.80|58.33|36.90|91.66|34.52|26.19|21.42|33.33
| Marketing               |40.24|74.39|60.97|96.34|74.39|100|80.48|69.51|92.68|81.70|62.19|70.73|45.12|68.29|43.90|93.90|25.60|30.48|22.23|40.24
| Product Management      |61.70|74.46|63.82|93.61|78.72|100|74.46|61.70|97.87|80.85|73.40|57.44|43.61|68.08|35.10|96.80|28.72|34.04|22.53|42.55
| Research and Development|63.38|70.42|54.92|95.77|83.09|100|81.69|63.38|97.18|80.28|64.78|61.97|43.66|70.42|32.39|91.54|33.80|30.98|22.53|19.71
| Sales                   |59.57|74.46|60.63|96.80|76.59|100|79.78|68.08|94.68|75.53|63.82|71.27|50.00|68.08|28.72|96.80|28.72|30.85|21.27|46.23
| Services                |62.22|64.44|60.00|95.55|77.77|100|81.11|63.33|96.66|80.00|71.11|52.22|58.88|67.77|36.66|94.44|25.55|41.11|28.88|28.88
| Support                 |57.29|64.58|61.45|94.79|80.20|100|76.04|68.75|90.62|72.91|73.95|54.16|50.00|63.54|34.37|94.79|27.08|34.37|20.83|30.20
| Training                |55.55|73.61|66.66|95.83|80.55|100|88.88|61.11|94.44|75.00|65.27|55.55|52.77|70.83|36.11|93.05|36.11|29.16|22.22|33.33
- There is significant differences between employees based on Department for many questions. These should be examined further.


### eNPS
| Level               | Mean | Std |
|--------------------|-------|------|
| Accounting              |7.66|1.78
| Business Development    |6.93|2.16
| Engineering             |7.05|1.92
| Human Resources         |7.23|2.15
| Legal                   |7.16|1.78
| Marketing               |7.13|1.98
| Product Management      |7.03|1.82
| Research and Development|7.39|1.81
| Sales                   |7.18|2.03
| Services                |7.10|2.10
| Support                 |7.27|1.87
| Training                |7.44|1.81

| Department               |          eNPS Score |
|:-------------------------|-----------:|
| Accounting               |  0.16      |
| Business Development     | -0.0740741 |
| Engineering              | -0.0909091 |
| Human Resources          |  0.0136986 |
| Legal                    | -0.0833333 |
| Marketing                | -0.097561  |
| Product Management       | -0.106383  |
| Research and Development |  0.028169  |
| Sales                    | -0.0744681 |
| Services                 | -0.0555556 |
| Support                  | -0.03125   |
| Training                 |  0         |
- The Business Development, Engineering,Legal, Marketing, Sales, and Product Managment teams all scored the lowest.
- The Accounting and Training teams highly recommends the org.

### Metrics
| Department             |   Satisfaction Mean |   Satisfaction Std |   Wlb Mean |   Wlb Std |   Leadership Support Mean |   Leadership Support Std |   Manager Support Mean |   Nanager Support Std |   Inclusion Mean |   Inclusion Std |   Role Alignment Mean |  Role Alignment Std |
|:-------------------------|--------------------:|-------------------:|-----------:|----------:|-------------------------:|------------------------:|----------------------:|---------------------:|-----------------:|----------------:|---------------------:|--------------------:|
| Accounting               |               13.01 |               2.2  |       1.03 |      0.87 |                     4.19 |                    0.73 |                  4.04 |                 1.02 |             1.43 |            0.66 |                 1.32 |                0.76 |
| Business Development     |               12.8  |               2.25 |       0.91 |      0.74 |                     4.07 |                    0.79 |                  4.21 |                 0.79 |             1.3  |            0.81 |                 1.23 |                0.64 |
| Engineering              |               13.02 |               2.25 |       0.93 |      0.71 |                     4.02 |                    0.86 |                  4.16 |                 0.81 |             1.39 |            0.72 |                 1.4  |                0.81 |
| Human Resources          |               12.48 |               2.46 |       0.86 |      0.75 |                     4.08 |                    0.89 |                  3.97 |                 0.99 |             1.36 |            0.69 |                 1.18 |                0.77 |
| Legal                    |               12.99 |               2.27 |       0.81 |      0.7  |                     4.23 |                    0.81 |                  4.15 |                 0.83 |             1.43 |            0.73 |                 1.3  |                0.88 |
| Marketing                |               12.93 |               2.13 |       0.93 |      0.78 |                     4.06 |                    0.81 |                  4.09 |                 0.88 |             1.44 |            0.69 |                 1.38 |                0.84 |
| Product Management       |               12.89 |               2.25 |       0.99 |      0.74 |                     4.11 |                    0.92 |                  4.09 |                 0.83 |             1.36 |            0.72 |                 1.32 |                0.66 |
| Research and Development |               12.62 |               2.39 |       0.73 |      0.74 |                     4.04 |                    0.8  |                  3.99 |                 1.01 |             1.34 |            0.67 |                 1.37 |                0.85 |
| Sales                    |               12.83 |               2.21 |       0.89 |      0.74 |                     4.09 |                    0.86 |                  4.07 |                 0.85 |             1.43 |            0.71 |                 1.26 |                0.7  |
| Services                 |               12.87 |               2.46 |       0.99 |      0.81 |                     3.98 |                    0.86 |                  3.98 |                 0.85 |             1.28 |            0.81 |                 1.3  |                0.85 |
| Support                  |               12.5  |               2.34 |       0.85 |      0.7  |                     4.01 |                    0.92 |                  3.96 |                 0.91 |             1.33 |            0.72 |                 1.25 |                0.81 |
| Training                 |               12.86 |               2.13 |       0.85 |      0.73 |                     4.17 |                    0.77 |                  3.89 |                 0.86 |             1.35 |            0.77 |                 1.43 |                0.85 |
- Support, R+D, HR, and BD scored lower on satisfaction
- Accounting, Engineering, Legal scored highest on satisfaction
- There was high varience in Services, R+D, and HR on satisfaction
- Legal, R+D, Support, Training, HR scored the lowest on wlb.
- Accounting, Services, Marketing, and Engineering scored the highest on wlb.
- Engineering, R+D, Services, Marketing, HR scored low on leadership support.
- Training and Accounting scored highon leadership support.
- Values were generally consistant across departments on leadership support.
- Training, HR, Services, Support scored lower on manager support.
- Marketing and Product Managment scored high on manager support.
- Values were generally consistant across departments on manager support.
- Values are similar but the Services team is the lowest on inclusion.
- HR, BD, and Support stand out on the low end on role alignment.
- Training, Marketing, and R+D stand out on the high end on role alignment.

# Examine Female Employee Metrics Further
## Race
### Metrics
| Race             |    Male Satisfaction Mean |    Female Satisfaction Mean |   Male WLB Mean |   Female WlB Mean |   Male Leadership Support Mean |   Female Leadership Support Mean |  Male Manager Support Mean |   Female Manager Support Mean |   Male Inclusion Mean |  Female Inclusion Mean |   Male Role Alignment Mean |  Female Role Alignment Mean |
|:-----------------|-------------------------:|---------------------------:|----------------:|------------------:|------------------------------:|--------------------------------:|---------------------------:|-----------------------------:|----------------------:|------------------------:|--------------------------:|----------------------------:|
| African American |                    11.82 |                      10.63 |            0.89 |              0.7  |                          3.86 |                            3.72 |                       3.86 |                         3.2  |                  0.59 |                    0.78 |                      1.25 |                        1.43 |
| Asian            |                    13.71 |                      12.62 |            1.08 |              0.78 |                          4.29 |                            4.14 |                       4.46 |                         3.85 |                  1.55 |                    1.52 |                      1.27 |                        1.33 |
| Caucasian        |                    14.74 |                      11.82 |            1.02 |              0.79 |                          4.58 |                            3.82 |                       4.72 |                         3.66 |                  1.93 |                    1.24 |                      1.29 |                        1.29 |
| Hispanic         |                    12.08 |                      10.49 |            1.1  |              0.78 |                          3.69 |                            3.42 |                       3.98 |                         3.27 |                  0.59 |                    0.62 |                      1.37 |                        1.36 |
| Other            |                    11.48 |                      10.55 |            0.87 |              0.8  |                          3.48 |                            3.45 |                       3.87 |                         3.25 |                  0.57 |                    0.75 |                      1.39 |                        1.4  |
- Women of color tended to have less overall satisfaction
- Asian women stood out as positive outliers for satisfaction
- Work life balance was fairly balanced across race
- Women of color tended to have less overall support from their managers
- Asian women stand out as a positive outlier for leadership support
- Leadership support is fairly balanced
- Asian women stand out as a positive outlier

## Department
### Metrics
| Department             |    Male Satisfaction Mean |    Female Satisfaction Mean |   Male WLB Mean |   Female WlB Mean |   Male Leadership Support Mean |   Female Leadership Support Mean |  Male Manager Support Mean |   Female Manager Support Mean |   Male Inclusion Mean |  Female Inclusion Mean |   Male Role Alignment Mean |  Female Role Alignment Mean |
|:-------------------------|-------------------------:|---------------------------:|----------------:|------------------:|------------------------------:|--------------------------------:|---------------------------:|-----------------------------:|----------------------:|------------------------:|--------------------------:|----------------------------:|
| Accounting               |                    14.02 |                      11.86 |            1.15 |              0.89 |                          4.42 |                            3.91 |                       4.53 |                         3.49 |                  1.55 |                    1.29 |                      1.35 |                        1.29 |
| Business Development     |                    13.52 |                      11.95 |            1.09 |              0.7  |                          4.32 |                            3.78 |                       4.45 |                         3.92 |                  1.32 |                    1.27 |                      1.2  |                        1.27 |
| Engineering              |                    13.89 |                      12.02 |            0.98 |              0.88 |                          4.21 |                            3.8  |                       4.53 |                         3.73 |                  1.57 |                    1.17 |                      1.32 |                        1.49 |
| Human Resources          |                    13.79 |                      10.71 |            0.95 |              0.74 |                          4.33 |                            3.74 |                       4.57 |                         3.16 |                  1.6  |                    1.03 |                      1.26 |                        1.06 |
| Legal                    |                    14.02 |                      11.79 |            0.96 |              0.64 |                          4.47 |                            3.95 |                       4.56 |                         3.69 |                  1.56 |                    1.28 |                      1.16 |                        1.46 |
| Marketing                |                    13.71 |                      12.25 |            1.16 |              0.73 |                          4.21 |                            3.93 |                       4.42 |                         3.8  |                  1.53 |                    1.36 |                      1.18 |                        1.55 |
| Product Management       |                    13.85 |                      11.94 |            1.02 |              0.96 |                          4.28 |                            3.94 |                       4.51 |                         3.66 |                  1.53 |                    1.19 |                      1.32 |                        1.32 |
| Research and Development |                    14    |                      11.55 |            0.87 |              0.62 |                          4.26 |                            3.88 |                       4.52 |                         3.58 |                  1.55 |                    1.18 |                      1.48 |                        1.27 |
| Sales                    |                    14.17 |                      11.1  |            1.08 |              0.66 |                          4.38 |                            3.71 |                       4.51 |                         3.51 |                  1.62 |                    1.17 |                      1.38 |                        1.1  |
| Services                 |                    13.43 |                      12.27 |            0.98 |              1    |                          4.13 |                            3.82 |                       4.28 |                         3.66 |                  1.48 |                    1.07 |                      1.24 |                        1.36 |
| Support                  |                    13.76 |                      11.39 |            0.98 |              0.75 |                          4.31 |                            3.75 |                       4.44 |                         3.53 |                  1.51 |                    1.18 |                      1.29 |                        1.22 |
| Training                 |                    14.25 |                      11.75 |            1.03 |              0.7  |                          4.53 |                            3.88 |                       4.41 |                         3.48 |                  1.69 |                    1.08 |                      1.44 |                        1.42 |
- Women in HR, Sales, and Support stood out as lower overall satisfaction
- Marketing and Services stood out as having high satisfaction
- Product Managment, Accounting and Services stood out while still relatively low work life balance
- Given how much of an outlier Accounting is when not controlling for Gender, this is concerning
- Research and Development, Legal, and Sales stand out on the low end of work-life balance
- Leadership support was fairly standard across departments
- Accoutning is a slight positive outlier in leadership support
- Manager suport was fairly standard across departments
- BD stands out as a positive outlier in manager support

## Level
### Metrics 
| Level             |    Male Satisfaction Mean |    Female Satisfaction Mean |   Male WLB Mean |   Female WlB Mean |   Male Leadership Support Mean |   Female Leadership Support Mean |  Male Manager Support Mean |   Female Manager Support Mean |   Male Inclusion Mean |  Female Inclusion Mean |   Male Role Alignment Mean |  Female Role Alignment Mean |
|:------------|-------------------------:|---------------------------:|----------------:|------------------:|------------------------------:|--------------------------------:|---------------------------:|-----------------------------:|----------------------:|------------------------:|--------------------------:|----------------------------:|
| Entry Level |                    13.76 |                      11.82 |            1.05 |              0.74 |                          4.32 |                            3.88 |                       4.4  |                         3.68 |                  1.53 |                    1.27 |                      1.31 |                        1.28 |
| Executive   |                    14.45 |                      11.27 |            0.75 |              0.64 |                          4.6  |                            3.73 |                       4.7  |                         3.45 |                  1.75 |                    1.27 |                      1.4  |                        1.36 |
| Junior      |                    13.77 |                      11.69 |            0.94 |              0.84 |                          4.28 |                            3.85 |                       4.52 |                         3.53 |                  1.5  |                    1.14 |                      1.24 |                        1.33 |
| Mid-Level   |                    14.12 |                      11.75 |            1.17 |              0.7  |                          4.41 |                            3.72 |                       4.53 |                         3.6  |                  1.56 |                    1.16 |                      1.22 |                        1.48 |
| Senior      |                    14.2  |                      11.54 |            1.17 |              0.88 |                          4.2  |                            3.83 |                       4.51 |                         3.67 |                  1.66 |                    0.96 |                      1.57 |                        1.21 |
- Satisfaction tends to decline as Women increase in level in the organization that should be examined further
- Work life balance is balanced except for the Executive level which stands out as a negative outlier this is not surprising
- Leadership support is balanced across level
- Manager support is fairly balanced across level

