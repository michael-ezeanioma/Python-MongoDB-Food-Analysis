# Overview

Employing Python, MongoDB, and PyMongo, this project analyzes food hygiene ratings from the UK Food Standards Agency to help journalists and food critics at Eat Safe, Love focus their reporting. The project involves setting up a NoSQL database, updating records, and performing exploratory data analysis to extract meaningful insights from restaurant ratings.

# Project Components

__1. Database and Jupyter Notebook Setup:__ Load establishments.json into MongoDB using the terminal, then create the uk_food database and establishments collection. Verify the database and collection setup in Jupyter Notebook, and assign the establishments collection to a variable for querying.

__2. Database Updates:__ Add the new restaurant Penang Flavours in Greenwich to the database, then retrieve and update the BusinessTypeID for "Restaurant/Cafe/Canteen." Remove all establishments in the Dover Local Authority and convert the latitude, longitude, and RatingValue fields from strings to numerical values.

__3. Exploratory Data Analysis:__ Identify establishments with a hygiene score of 20 and find those in London with a RatingValue of 4 or higher. Determine the top 5 highest-rated establishments nearest to Penang Flavours, and count establishments with a hygiene score of 0, grouping them by Local Authority and sorting from highest to lowest.

# Files

__NoSQL_setup_starter.ipynb:__ Jupyter Notebook for database setup and updates.

__NoSQL_analysis_starter.ipynb:__ Jupyter Notebook for exploratory 

__analysis.establishments.json:__ JSON file containing food hygiene rating data.

# Key Features

__Database Setup:__ Imports raw food hygiene data into MongoDB and verifies the integrity of the database and collection structure.

__Data Cleaning & Updates:__ Adds new records and updates missing or incorrect values and emoves unwanted data (Dover establishments). Additonally, converts string-based numerical fields into appropriate data types.

__Data Analysis & Insights:__ Uses MongoDB queries to find high-risk and top-rated establishments while identifying areas with high hygiene concerns for food critics to investigate.

# Dependencies

__MongoDB:__ NoSQL database for storing and querying data.

__PyMongo:__ Python library for interacting with MongoDB.

__Pandas:__ Converts query results into DataFrames for analysis.

__Jupyter Notebook:__ Interactive development environment for data exploration.

# Technologies Used

__Python:__ Core programming language for data processing.

__MongoDB:__ NoSQL database for flexible data storage.

__PyMongo:__ Facilitates MongoDB queries and updates.

__Pandas:__ Enables DataFrame-based analysis.

# How to Use

1. Clone this repository to your local environment

2. Install required dependencies
3. Import the dataset into MongoDB

4. Open and run NoSQL_setup_starter.ipynb for database setup and updates

5. Open and run NoSQL_analysis_starter.ipynb to perform data analysis and generate insights
<!--Mod 12-->
