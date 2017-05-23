# DATA-DUKE-Bayes-Reg
The following files were submitted for the first project of Duke University's Bayesian Statistics course hosted by Coursera

### Submission by Connor Lenio. Email: cojamalo@gmail.com
Completion Date: May 23, 2017

### Please visit https://cojamalo.github.io/DATA-DUKE-Bayes-Reg/bayesian_project.html to properly view the project html file.

### Introduction to the Data
From "Data Analysis Project Information":

Congratulations on getting a job as a data scientist at Paramount Pictures! Please see the Data Analysis Project for your assignment. Below you will find the files that you will need.

Your boss has just acquired data about how much audiences and critics like movies as well as numerous other variables about the movies. This dataset is provided below, and it includes information from Rotten Tomatoes and IMDB for a random sample of movies.

She is interested in learning what attributes make a movie popular. She is also interested in learning something new about movies. She wants you team to figure it all out.

As part of this project you will complete exploratory data analysis (EDA), modeling, and prediction.

The specific modeling task you need to complete is as follows: Develop a Bayesian regression model to predict audience_score from the following explanatory variables. Note that some of these variables are in the original dataset provided, and others are new variables you will need to construct in the data manipulation section using the mutate function in dplyr:

* feature_film: "yes" if title_type is Feature Film, "no" otherwise
* drama: "yes" if genre is Drama, "no" otherwise
* runtime
* mpaa_rating_R: "yes" if mpaa_rating is R, "no" otherwise
* thtr_rel_year
* oscar_season: "yes" if movie is released in November, October, or December (based on thtr_rel_month), "no" otherwise
* summer_season: "yes" if movie is released in May, June, July, or August (based on thtr_rel_month), "no" otherwise
* imdb_rating
* imdb_num_votes
* critics_score
* best_pic_nom
* best_pic_win
* best_actor_win
* best_actress_win
* best_dir_win
* top200_box

All analysis must be completed using the R programming language via RStudio, and your write up must be an R Markdown document. To help you get started we provide a template Rmd file below (see Rmd template in the Required files section below). Download this file, and fill in each section.

NOTE: If you have previously completed the Course 3 in the Statistics with R Specialization (Linear Regression and Modeling) you should be familiar with this dataset. While the dataset is the same, the tasks you are asked to carry out for this project are different.


### The Scripts
This project feautures a RMarkdown document produced in RStudio and knitted to HTML. Please view the .html, .Rmd, or .md file for an overview of both the assignment questions and my responses.

Project coded by Connor Lenio ©2017. 
