# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Part 2: Dataset + Data Collection

## Overview

Based on the feedback you received from your lightning talk, choose **one** of your topic areas to move forward. For Part 2, you'll need to collect, clean, and document the dataset(s) you intend to use for your project.

This is not always a trivial task. Remember that data acquisition, transformation, and cleaning are typically the most time-consuming parts of data science projects, so don’t procrastinate!

Once you have your data, read into it and review it to confirm whether it is as productive as you intended. If not, switch datasets, gather additional data (e.g. multiple datasets), or revise your project goals. 

Create your own database and data dictionary, then clean and munge your data as appropriate. Finally, document your work so far.

**Goal**: Find the data you need for your project, clean, and document it.

---

## Requirements

1. Find and Clean Your Data: Source and format the required data for your project. 
   - Create a database
   - Create a data dictionary
2. Perform preliminary data munging and cleaning of your data: organize your data relevant to your project goals. 
   - Review data to verify initial assumptions
   - Clean and munge data as necessary
3. Describe your data: keep your intended audience(s) in mind.
   - Document your work so far in a Jupyter notebook. 

#### Bonus

4. Document your project goals (revise from your initial pitch)
   - Articulate “Specific aim”
   - Outline proposed methods and models
   - Define risks & assumptions

5. Create a blog post of at least 500 words that describes your work so far. Link to it in your Jupyter notebook.

---

## Deliverable Format & Submission

- Table, file, or database with relevant text file or notebook description.

---

## Suggested Ways to Get Started

- Review your initial proposal topic and feedback, and revise accordingly. 
- Spend time with your data and verify that it can help you accomplish the goals you set out to pursue. 
- If not, document how you intend to either change those goals. 
- Alternatively, go find some additional data and/or try another source.

---

## Useful Resources

- [Exploratory Data Analysis](http://insightdatascience.com/blog/eda-and-graphics-eli-bressert.html)
- [Best practices for data documentation](https://www.dataone.org/all-best-practices)

---

## Project Feedback + Evaluation

[Attached here is a complete rubric for this project.](./capstone-part-02-rubric.md)

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
|  I have found datasets at Football Outsiders https://www.footballoutsiders.com/user/241456/home and made an initial model and projection for Week 1 of the 2021 NFL season. The data has been imported into the jupyter notebook and structured to make predictions as suggested. I am looking forward to seeing if the model was correct this week. Then I can update these results and put it into the model. So far the data  is sufficient for the capstone, but I'm not happy with the ways my train data is performing on the test data.  I believe my model may be overfit. Moreover, the std deviations from my cross validation are wide. Moreover, I'm using last year's data as the season is just starting. It is difficult to incorporate all of the player movement to get a better prediction. Consequently, I've acquired another dataset two days ago to improve upon the performance of the model from Pro Football Focus https://premium.pff.com/nfl/teams?season=2020&weekGroup=REG The struggles are manipulating the data into a form that is usable. It takes awhile. I also wanted to gamble on the model, but DraftKings requires you to go to St. Louis before making online bets. I live in the Chicagoland area. I'm going to go to Rivers in Chicago to see if I can make bets for next week. In the original dataset, I've used DVOA (Defense Adjusted Value Over Average) scores for offense, defense, and special teams.  The data dictionary is at this  website https://www.footballoutsiders.com/info/methods  which defines the metric. I'm comparing the teams' scores in DVOA from the week prior to the prediction week to mimic actual forecasting.                  |                |                   |
