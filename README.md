# Bavda Consulting

# Vivek Bavda


# "On any given Sunday, you are either going to win or lose."


## Problem Statement

The above quote from Al Pacino's character in the movie *Any Given Sunday* is interpretable as a search for certainty in a high stakes world with no uncertainty. While there is no certainty in football except this aphorism, wouldn't be interesting if we could take at least a little bit of the uncertainty out of who will win? No doubt, the games have to be played. However, this analysis attempts to use supervised machine learning to predict winners and losers from 2020 NFL football gamesand beyond. This, of course is the holy grail. While NFL fans believe with absolute certainty that they are Nostradamus, these predictions often lead to disappointment and the loss of money at casinos. Moreover, given the U.S. Supreme Court's decision to remove the restrictions on sports betting in states, NFL fans are lining up outside the door to make bets including the author of this study. Win or lose--if you take the time to read this study, you will see one individual's path attempt to hold the Holy Grail.

Recommendation: While there are multiple sources of data including ESPN, Football Outsiders, Sports Betting Books(the wisdom of the crowd), and Pro Football Focus, this study finds the data from Football Outsiders with the wisdom of the crowd to be the most relevant to determining high probability predictions. Moreover, the use of a Grid Searched Support Vector Machine to model this data reaches a 68% accuracy on cross validated data in predicting NFL winners and losers from week to week, 

## Table of Contents in the Repository


A Jupyter Notebook 
BavdaConsultingNFLCapstone  showing the introduction, background, outside research, data set information, and data collection function, processing, modeling, and conclusion.

The following are the datasets in the Data Folder in the repository:

2020_Team_DVOA_Ratings_Overall_after_Week_1
2020_Team_DVOA_Ratings_Overall_after_Week_1_convert.csv
2020_Team_DVOA_Ratings_Overall_after_Week_1.csv
2020_Team_DVOA_Ratings_Overall_after_Week_1convert.csv
2020_Team_DVOA_Ratings_Overall_after_Week_1edit.csv
2020_Team_DVOA_Ratings_Overall_after_Week_1projected
2020_Team_DVOA_Ratings_Overall_after_Week_2
2020_Team_DVOA_Ratings_Overall_after_Week_2 _convert.csv
2020_Team_DVOA_Ratings_Overall_after_Week_2.csv
2020_Team_DVOA_Ratings_Overall_after_Week_3
2020_Team_DVOA_Ratings_Overall_after_Week_3_convert.csv
2020_Team_DVOA_Ratings_Overall_after_Week_3.csv
2020_Team_DVOA_Ratings_Overall_after_Week_4
2020_Team_DVOA_Ratings_Overall_after_Week_4.csv
2020_Team_DVOA_Ratings_Overall_after_Week_4a.csv
2020_Team_DVOA_Ratings_Overall_after_Week_4a.xlsx
2020_Team_DVOA_Ratings_Overall_after_Week_5
2020_Team_DVOA_Ratings_Overall_after_Week_5.csv
2020_Team_DVOA_Ratings_Overall_after_Week_5a.csv
2020_Team_DVOA_Ratings_Overall_after_Week_6.csv
2020_Team_DVOA_Ratings_Overall_after_Week_7.csv
2020_Team_DVOA_Ratings_Overall_after_Week_8.csv
2020_Team_DVOA_Ratings_Overall_after_Week_9.csv
2020_Team_DVOA_Ratings_Overall_after_Week_10.csv
2020_Team_DVOA_Ratings_Overall_after_Week_11.csv
2020_Team_DVOA_Ratings_Overall_after_Week_12.csv
2020_Team_DVOA_Ratings_Overall_after_Week_13.csv
2020_Team_DVOA_Ratings_Overall_after_Week_14.csv
2020_Team_DVOA_Ratings_Overall_after_Week_15.csv
2020_Team_DVOA_Ratings_Overall_after_Week_16.csv
2020_Team_DVOA_Ratings_Overall_after_Week_17.csv
2020_Team_DVOA_Ratings_Overall.csv
2021 Team DVOA Ratings, Overall after Week 1
2021 Team DVOA Ratings, Overall after Week 1.csv
2021 Team DVOA Ratings, Overall after Week 2
2021 Team DVOA Ratings, Overall after Week 2.csv
2021_Team_DVOA_Ratings_Overall_after_Week_1test.csv
2021_Team_DVOA_Ratings_Overall_after_Week_2_convert.csv
2021_Team_DVOA_Ratings_Overall_after_Week_3
2021_Team_DVOA_Ratings_Overall_after_Week_3.csv
2021_Team_DVOA_Ratings_Overall_after_Week_3convert.csv
2021_Week1.test.2020endinputs.csv
2021_Week1.test2020_Team_DVOA_Ratings_Overall_after_Week_17
CapstonePFFData.xlsx
CapstonePFFDatahelp.xlsx
FinalWeek1Projections
FinalWeek2Projections
FinalWeek3Projections
FinalWeek4Projections
VLB2020Playoffs.csv
VLBWeek6.csv
VLBweek7.csv
VLBWeek8.csv
VLBWeek9.csv
VLBWeek10.csv
VLBWeek11.csv
VLBWeek12.csv
VLBWeek13.csv
VLBWeek14.csv
VLBWeek15.csv
VLBWeek16.csv
nflodds2020-21-2.xlsx

Presentation slides can be found

And this Readme.md




## Analysis and Conclusions

As the introduction explains, the NFL is full of uncertainty. It has more parity than any other sport. To be able to measure it and quantify it requires immense precision. To most, it would be the Holy Grail of sports prediction. In this endeavor, I would make three recommendations.

First, the production model chosen is Gridsearched Support Vector Machines for several reasons, most importantly, that the Cross Validation Score and  Accuracy Score were the highest above its competitors

The second recommendation is based off both exploratory data analysis. This suggests that offensive prowess is far more important than defensive prowess or special teams. The correlation heat map emphasizes offense over the other groups on a team.

The third recommendation is that Football Outsiders data is probably the best

### **[Capstone, Part 4: Findings + Technical Report][part-4]**

Share your technical findings with your fellow data scientists. Explain your goals, describe modeling choices, evaluate model performance, and discuss results. Data science reporting is technical, but don’t forget that you should tell a compelling story about your data.

- **Requirements**: Summarize your goals and metrics for success, variables of interest, and removal of any outliers or data imputation. Your process description should be concise and relevant to your goals. Summarize statistical analysis, including model selection,  implementation, evaluation, and inference. Be convincing – justify all important decisions! Clearly label plots and visualizations. Include an Executive Summary
- **Format:** Jupyter Notebook(s)


### **[Capstone, Part 5: Presentation + Non-Technical Summary][part-5]**

Take your findings and share a 10 minute presentation that delivers the most important insights from your project to a non-technical audience. Tell us the most interesting story about your data. Break down your process for a novice audience. Make sure to include compelling visuals. Time is short, so be sure to practice and include only the most relevant components of your project.

- **Requirements**: Convey your goals, limits/assumptions, methods and their justification, findings, and conclusions. Define technical terms. Include graphics and visualizations
- **Format:** Interactive graphic presentation, website, or slide deck
