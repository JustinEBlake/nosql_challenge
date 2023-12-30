# Module 12 Challenge

## Project Overview 
- The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Part 1: Database and Jupyter Notebook Set Up
- Import data
- List the Databases and collections of `uk_food` db.
- Assign `establishments` collection to a variable.

## Part 2: Update the Database
- Insert data for Penang Flavours Restaurant
- Update Penang Flavors' `BusinessID`
- Convert all `latitude` and `longitude` fields to float
- Convert all `RatingValue` fields to integers

📁 nosql_challenge/[NoSQL_setup_starter.ipynb](https://github.com/JustinEBlake/nosql_challenge/blob/master/NoSQL_setup_starter.ipynb)

## Part 3: Exploratory Analysis
- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a `RatingValue` greater than or equal to 4?
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

📁 nosql_challenge/[NoSQL_analysis_starter.ipynb](https://github.com/JustinEBlake/nosql_challenge/blob/master/NoSQL_analysis_starter.ipynb)

## Source Code
- Source Code from [pymongodb documentation](https://pymongo.readthedocs.io/en/stable/examples/aggregation.html) & lessons throughout curriculum.