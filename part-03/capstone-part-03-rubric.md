# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) CAPSTONE, PART 3: RUBRIC

## Data Science Immersive | Capstone, Part 3		
Your project criteria were derived from the following standards, taken from our data science workflow:

- [ ] Mine Data
- [ ] Refine Data
- [ ] Model Data

Acceptable performance for these standards is based on how well you've performed the specific requirements listed below.

---

## Performance Evaluation
> Instructors: Mark sections with an `X` or `n/a` if a score does not apply. Grades and indiviual feedback are only necessary for **"Required"** sections; bonus objectives are primarily intended for student enrichment.

#### RUBRIC
Score  | Expectations
--- | ---
**0** | _Incomplete._
**1** | _Does not meet expectations._
**2** | _Meets expectations, good job!_


#### REQUIRED
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

## Score:
Based on the requirements, it is possible to earn a maximum of  **X**  points on this project. Your score is: **X**

- Remember, total scores are helpful as an indicator of how well you followed project instructions, but the most important feedback is to follow up on any actionable advice from your instructors for improving your project in the future!

---

> Note: The following section is an optional format for providing feedback on a student's overall progress in the course. Use of this format may vary by market; check with your local instructional team for more details.

## PROGRESS REPORT
**Student Check-in:**

|WHAT’S GOING WELL/STRUGGLES|DEVELOPMENT PLAN|INSTRUCTOR FEEDBACK|
|---------------------------|----------------|-------------------|
|                           |                |                   |
In my exploratory data analysis, I've used the Football Outsiders dataset. This is cleaned. I've also added the historical Las Vegas odds for games for 2020 and beyond. I looked at the descriptive statistics. I noticed I have a data entry/coding mistake in the W-L and W-L.1 columns, which I will correct. I've created histograms for each relevant features. I've attempted to look offensive, defensive, and special teams metrics. I used barplots and scatterplots from seabron. I've created a correlation heatmap to get an idea of linearity and for logistic regression. I've used seaborn to plot the logistic regression fitted line between 1 and 0 on several features. One interesting thing is that ranking of offensive, Defensive, and Special Teams rankings did better than their raw and weighted scores.  The Las Vegas odds are the best predictor. My hope was this would influence rather than take on a leading role in the model. There are a few outliers. However, these are not an issue because based on domain knowledge, this actually made a lot of sense. There were some really bad teams. There are a lot of risks and limitations. I'm looking at a 66% accuracy rate.I have 2020 and 2021 data. I may need more data historically although it is not clear that this will make a difference. There is a level of randomness to these games. Moreover, if someone solved this, Vegas would be out of business. That is a likely limitation.  In getting my accuracy rate, I've used logistic regression, knn, randomforests, neural networks, gridsearch neural networks, svm, and svm gridsearched. The latter gave me my best score.  Beyond getting more of the data I have, I would like to get more detailed data of the existing dataset to push up the accuracy rate to 70%. This involves using ProFootballFocus data. I also want to use recurrent neural networks and model by NFL team to see if I can improve accuracy rather than NFL wide numbers.
