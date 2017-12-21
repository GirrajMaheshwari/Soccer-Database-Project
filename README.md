# Soccer-Database-Project
Soccer Database Project
Our project aims to create a database which can be utilized to predict outcomes, entertaining stories reporting statistics that enhance the viewers experience of soccer matches and gathering valuable insights to make relevant comparisons by considering player data, match data and corresponding data from soccer leagues. Data utilized for this project has been taken from past two years. The leagues for which data is mined are from English Premier League and La-Liga.

Database Solution Outline
•	Data Sources:
o	ESPN FC Census - Match data was extracted from this website.
o	world football net api - Player attributes were web scraped from this website.
o	Twitter – User reviews about teams were extracted for sentiment analysis

•	Data extraction:
o	Data extracted from source HTML content using python libraries 'BeautfulSoup4' and 'getlibrary'
o	User reviews on teams from twitter.

•	Model creation steps:
o	Conceptualized and created Crow foot ER diagram considering entities and attributes of soccer
o	Creation of ID for each attribute in various tables
o	Normalization of data to 3NF

•	Database integration and setup:
o	MySQL 6.3 used for creation of SQL tables and data loading

•	Data analysis:
o	Data analyzed by creating SQL queries and visualized using Tableau
o	Sentiment analysis of user reviews using Semantria excel add-on. 
