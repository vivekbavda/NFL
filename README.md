# Bavda Consulting

# Vivek Bavda


# "On any given Sunday, you are either going to win or lose."


## Problem Statement

The above quote from Al Pacino's character in the movie *Any Given Sunday* is interpretable as a search for certainty in a high stakes world with no uncertainty. While there is no certainty in football except this aphorism, wouldn't be interesting if we could take at least a little bit of the uncertainty out of who will win? No doubt, the games have to be played. However, this analysis attempts to use supervised machine learning to predict winners and losers from 2020 NFL football gamesand beyond. This, of course is the holy grail. While NFL fans believe with absolute certainty that they are Nostradamus, these predictions often lead to disappointment and the loss of money at casinos. Moreover, given the U.S. Supreme Court's decision to remove the restrictions on sports betting in states, NFL fans are lining up outside the door to make bets including the author of this study. Win or lose--if you take the time to read this study, you will see one individual's path attempt to hold the Holy Grail.

Recommendation: While there are multiple sources of data including ESPN, Football Outsiders, Sports Betting Books(the wisdom of the crowd), and Pro Football Focus, this study finds the data from Football Outsiders with the wisdom of the crowd to be the most relevant to determining high probability predictions. Moreover, using a Grid Searched Voter Classification model, this data reaches a 66% accuracy on cross validated data in predicting NFL winners and losers from week to week, 

## Table of Contents in the Repository


A Jupyter Notebook BavdaNFLCapstone  showing the introduction, background, outside research, data set information, and data collection function, processing, modeling, and conclusion.

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

As the introduction explains, Bavda Consulting has taken on predicting wins and losses in the NFL to add to the knowledge base surrounding the NFL and its games. This is of course, the holy grail of sports predictions for many reasons.  First of all, this is most popular sport in the U.S. Second, there is probably the most parity in this league than any other. Third, there is alot of unpredictability in the league. Finally, there is so much coordination and complexity with all of the people on the field to make a play successful or not.  Given these difficulties, this is a difficult problem. Moreover, this model was built with publicly available datasets. Having said that, using the wisdom of the crowd, expert judgment, and traditional data, this model has beaten the baseline and achieved the industry standard, which is approximately 66-68 percent. This bodes well in terms of second and third phase of this project Phase 2 will turn this into a multiclassification model with a custom  loss function optimized for moneyline gambling. The third phase will be using recurrent neural nets and reinforcement models to better the model. Regardless of future endeavors, Bavda Consulting can make two key recommendations with this dataset. First, there is a production model recommendation, Second, there is a usage recommendation.


Production Model Recommendation
The production model chosen is Gridsearched Voter Classification model for several reasons. First, the accuracy score through cross validation and through the gambling choice was the highest. The visualizations in the confusion matrices and classification metric tables show makes a strong case. 

Second, the next highest model on the gambling accuracy score is KNN. Since the voter classifer includes KNN as one of the voters and the model works better with KNN as a voter, there is no reason to use KNN alone. Moreover, KNN is a weak learner and a simple model.  The voter classifier includes Adaboost and Gradient boosting, which increases KNN's ability to do better.

Third, while there are better models based on the accuracy in the cross validated sets, the proof is in the pudding. This model did well when we did not already know the outcome. While this could simply be aberration, it is unclear that GS SVM works well in this context. SVM is generally more powerful with high levels of dimensions. There also is not enough data for SVM. 

Model Usage Recommendation
The first recommendation is that this model is for learning and entertainment purposes. It does not guarantee any result. While gambling is mentioned, no one should believe this is a get rich scheme. However, it is an interesting exercise in a subject that many of us care about and enjoy.

The second recommendation is that instead of focusing on all aspects of the game, concentrate on the offense and its production. While every team in the NFL will argue that all phases in the game are important, offensive potency seems to be a better predictor. Differentiating the type of offensive production would make a big difference in determining who wins. A simple hypothesis would be that passing is more important than running. While defense wins championship is a common refrain, it seems that defense ought to be devalued. It may take a extraordinary defense to make up for a less potent offense. Special Teams seems to be even less important. In the process of feature selection, the increase in accuracy with special teams included was minor. 

The third recommendation is to use Football Outsiders data rather than Pro Football Focus. While Pro Football Focus has much expertise, their data did not seem to add more to the model. While similar variables existed for both datasets, Football Outsiders lead to higher accuracy scores. The wisdom of the crowd, moneyline, was a good predictor. In other words, odds in casinos do a good job of gauging the right margin. 

The fourth recommendation is to gather additional data over time for several reasons. I have approximately 600 data points. In retrospect, 1,600 data points would provide more context. I do intend to take in new data each week to improve the performance while also going further back. All of these models will perform better with more data.

This completes our analysis, conclusion, and recommendations. Please contact Bavda Consulting with any questions, suggestions and comments.