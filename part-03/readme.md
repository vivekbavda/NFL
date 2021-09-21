# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Part 3: EDA + Preliminary Analysis

## Overview

Begin quantitatively describing and visualizing your data. With rich datasets, EDA can go down an endless number of roads. Maintain perspective on your goals and scope your EDA accordingly. 

Managing your own time is a critical skill in analysis projects. Keep notes on your approach, results, setbacks, and findings! These will form the basis of your "progress report" to us for Part 3, as you meet with your instructors to discuss how things are going and what to do next.

**Goal**: A brief report that describes your EDA and analysis so far, as well as your concrete next steps.

---

## Requirements

1. Create a "progress report" that documents:
   - Your approach to exploratory data analysis
   - Your initial results
   - Any roadblocks, setbacks, or surprises
   
2. Perform initial descriptive and visual analysis of your data.
   - Identify outliers
   - Summarize risks and limitations 

3. Discuss your proposed next steps
   - Describe how your EDA will inform your modeling decisions
   - What are three concrete actions you need to take next?


#### BONUS

4. Visualize your EDA and approach using at least **two or more** of the data visualizations methods we've covered in class.
5. Create a blog post of at least 500 words explaining your EDA so far, including your results, setbacks, and lessons learned. Link to this in your notebook.

---

## Deliverable Format & Submission

- Format: Jupyter Notebook

---

## Suggested Ways to Get Started

- Document **everything** as you go! This will give you valuable material to pull into your report - and will paint a more accurate picture than trying to summarize afterward :)
- Be candid! This is not a race, but a chance to get valuable feedback. Be honest about what techniques have worked, what steps have taken you down the wrong turns, and what blockers you've run into.

---

## Useful Resources

- [Describing data visually](http://www.statisticsviews.com/details/feature/6314441/Visualising-Statistics-The-importance-of-seeing-not-just-describing-data.html)
- [Real world data science workflows often contain setbacks](https://guerrilla-analytics.net/2015/02/20/data-science-workflows-a-reality-check/)

---

## Project Feedback + Evaluation

[Attached here is a complete rubric for this project.](./capstone-part-03-rubric.md)

Your instructors will score each of your technical requirements using the scale below:

Score  | Expectations
--- | ---
**0** | _Incomplete._
**1** | _Does not meet expectations._
**2** | _Meets expectations, good job!_

## PROGRESS REPORT
**Student Check-in:**

|WHAT’S GOING WELL/STRUGGLES|DEVELOPMENT PLAN|INSTRUCTOR FEEDBACK|
|---------------------------|----------------|-------------------|
|                           |                |                   |
In my exploratory data analysis, I've used the Football Outsiders dataset. This is cleaned. I've also added the historical Las Vegas odds for games for 2020 and beyond. I looked at the descriptive statistics. I noticed I have a data entry/coding mistake in the W-L and W-L.1 columns, which I will correct. I've created histograms for each relevant features. I've attempted to look offensive, defensive, and special teams metrics. I used barplots and scatterplots from seabron. I've created a correlation heatmap to get an idea of linearity and for logistic regression. I've used seaborn to plot the logistic regression fitted line between 1 and 0 on several features. One interesting thing is that ranking of offensive, Defensive, and Special Teams rankings did better than their raw and weighted scores.  The Las Vegas odds are the best predictor. My hope was this would influence rather than take on a leading role in the model. There are a few outliers. However, these are not an issue because based on domain knowledge, this actually made a lot of sense. There were some really bad teams. There are a lot of risks and limitations. I'm looking at a 66% accuracy rate.I have 2020 and 2021 data. I may need more data historically although it is not clear that this will make a difference. There is a level of randomness to these games. Moreover, if someone solved this, Vegas would be out of business. That is a likely limitation.  In getting my accuracy rate, I've used logistic regression, knn, randomforests, neural networks, gridsearch neural networks, svm, and svm gridsearched. The latter gave me my best score.  Beyond getting more of the data I have, I would like to get more detailed data of the existing dataset to push up the accuracy rate to 70%. This involves using ProFootballFocus data. I also want to use recurrent neural networks and model by NFL team to see if I can improve accuracy rather than NFL wide numbers.
