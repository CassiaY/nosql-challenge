# Module 12: NoSQL Challenge  
<font size="3"> **Contributor:** Cassia Yoon  
**Github link:** https://github.com/CassiaY/nosql-challenge</font>

## Project Overview  
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, <i>Eat Safe, Love</i>, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.  
> The full assignment prompt is found in [Module_12_Challenge.pdf](/Module_12_Challenge.pdf).  

### Part 1: Database and Jupyter Notebook Set Up
1. Imported [establishments.json](/code/Resources/establishments.json) in the terminal. Created the database uk_food and collection establishments. Command text is found in the [NoSQL_setup_starter.ipynb](/code/NoSQL_setup_starter.ipynb).

### Part 2: Update the Database
1. Inserted a new restaurant to the database and removed establishments from the Dover area. Code can be found in [NoSQL_setup_starter.ipynb](/code/NoSQL_setup_starter.ipynb).

### Part 3: Exploratory Analysis
1. Explored the updated database to answer the below questions. Converted each result to a dataframe. See code and answers in the file [NoSQL_analysis_starter.ipynb](/code/NoSQL_analysis_starter.ipynb)  
    1. Which establishments have a hygiene score equal to 20?
    2. Which establishments in London have a RatingValue greater than or equal to 4?
    3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the newrestaurant added, "Penang Flavours"?
    4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Resources:
- 
- [UK Food Standards Agency](https://www.food.gov.uk/) (2022). UK food hygiene rating data API. [https://ratings.food.gov.uk/open-data/en-GB](https://ratings.food.gov.uk/open-data/en-GB). Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/opengovernment-licence/version/3/). Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072,

## Acknowledgements
Thank you to our teaching staff:
- Hunter Hollis
- Sam Espe
- Randy Sendek
