# NoSQL-challenge
This project evaluates food hygiene ratings across the UK to assist the editors of Eat Safe, Love in selecting establishments for future articles. The database, imported from establishments.json, holds food hygiene data and is analyzed to provide insights based on various factors such as hygiene scores, ratings, and location.

Part 1: Database Setup
Import Data: The data from the establishments.json file should be imported into MongoDB using the mongoimport command. The database should be named uk_food and the collection should be named establishments.

MongoDB Setup in Jupyter: The database connection should be established through the MongoDB client using PyMongo. Afterward, the database and collection should be accessed to confirm the import and view some documents.

Part 2: Database Updates
Add New Restaurant
A new halal restaurant, "Penang Flavours", needs to be added to the database. Its details, such as business type, address, contact information, and hygiene scores, should be inserted into the database.

Remove Dover Establishments
Establishments in the Dover Local Authority should be removed from the collection to comply with the magazine's focus.

Update Data Types
Some fields, like latitude, longitude, and RatingValue, may need to be converted to appropriate data types (e.g., strings to decimals) to ensure consistency and accurate querying.

Part 3: Exploratory Analysis
Hygiene Score of 20:
Query the database to find establishments with a hygiene score equal to 20.

Rating >= 4 in London:
Search for establishments located in London with a rating value of 4 or greater.

Top 5 Establishments Near "Penang Flavours":
Identify the top 5 establishments near the newly added "Penang Flavours" restaurant based on proximity and hygiene scores.

Local Authorities with Hygiene Score 0:
Group establishments by Local Authority and count how many establishments in each area have a hygiene score of 0, then sort the results from highest to lowest.

Resources: ChatGPT and Xpert Learning Assistant Chat+
