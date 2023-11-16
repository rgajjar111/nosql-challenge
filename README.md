# nosql-challenge
## Introduction
This README provides an overview of the steps taken in the Jupyter Notebook for setting up the database, updating data, and conducting exploratory analysis.

Part 1: Database and Jupyter Notebook Set Up
Import Data: Load the provided data from the establishments.json file into the MongoDB database named uk_food with a collection named establishments.

Jupyter Notebook Setup: Open the Jupyter Notebook and connect to the MongoDB database. Confirm the existence of the uk_food database and the establishments collection.

### Part 2: Update the Database
Add New Restaurant
Add a new halal restaurant, "Penang Flavours," to the database.

Update BusinessTypeID
Find and update the BusinessTypeID for the new restaurant.

Remove Establishments in Dover
Remove establishments in Dover from the database.

Update Data Types
Convert latitude and longitude to decimal numbers. Change the RatingValue to integer numbers.

### Part 3: Exploratory Analysis
Hygiene Score of 20: Identify establishments with a hygiene score of 20.

London Establishments with RatingValue >= 4: Find establishments in London with a RatingValue greater than or equal to 4.

Top 5 RatingValue 5 Establishments near "Penang Flavours": Locate the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score and nearest to "Penang Flavours."

Establishments with Hygiene Score of 0 in Each Local Authority: Determine the number of establishments with a hygiene score of 0 in each Local Authority area.
