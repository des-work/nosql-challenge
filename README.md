
# nosql-challenge

This repository contains files and Jupyter notebooks for the "NoSQL Challenge" project, where we explore and analyze food hygiene ratings data from the UK Food Standards Agency. The goal is to assist the editors of the food magazine, Eat Safe, Love, in evaluating establishments and providing insights for future articles.

## Part 1: Database and Jupyter Notebook Set Up

- Use `NoSQL_setup_starter.ipynb` for this section.
- Import the data from `establishments.json` into MongoDB, naming the database `uk_food` and the collection `establishments`.
- Import necessary libraries: PyMongo and Pretty Print (pprint).
- Confirm the database and data loading:
  - List databases, ensuring `uk_food` is listed.
  - List collections in the database, confirming `establishments` is present.
  - Display one document from the `establishments` collection using `find_one` and pprint.
- Assign the `establishments` collection to a variable for further use.

## Part 2: Update the Database

- Use `NoSQL_setup_starter.ipynb` for this section.
- Make requested modifications to the `establishments` collection:
  - Add a new halal restaurant in Greenwich with the provided information.
  - Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new restaurant.
  - Check and remove any establishments in the Dover Local Authority.
  - Use `update_many` to convert latitude, longitude, and RatingValue to appropriate numeric types.

## Part 3: Exploratory Analysis

- Use `NoSQL_analysis_starter.ipynb` for this section.
- Answer specific questions from Eat Safe, Love editors:
  - Identify establishments with a hygiene score equal to 20.
  - Find establishments in London with a RatingValue greater than or equal to 4.
  - Identify the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to "Penang Flavours."
  - Determine the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.

## Files

- `NoSQL_setup_starter.ipynb`: Jupyter notebook for setting up the database.
- `NoSQL_analysis_starter.ipynb`: Jupyter notebook for exploratory analysis.
- `establishments.json`: Data file containing food hygiene ratings information.

## Instructions for Use

1. Clone this repository to your local machine.
2. Add Jupyter notebook starter files (`NoSQL_setup_starter.ipynb` and `NoSQL_analysis_starter.ipynb`) and the `establishments.json` file to the repository folder.
3. Push the changes to your GitHub repository.

Feel free to explore the notebooks for detailed steps and explanations. Enjoy the challenge!
