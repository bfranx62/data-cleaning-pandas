# data-cleaning-pandas
## Ironhack Week 2 Quest Project - cleaning and analyzing shark attacks data. 

#### Group Members
Hoang Le Duc, Raynard Flores, Bryan Frank, Franklin Ledesma, and Rosemary Medina-Casanova

### Project Description
Python-based Shark Attack Analysis project aims to identify countries with the highest likelihood of shark incidents during June-August, assisting a Touring Company. We implement data cleaning, conduct exploratory data analysis (EDA), and deliver clear insights to fulfill the business case.

## Data Cleaning
- Identified and addressed relevant data quality issues.
- Implemented appropriate data cleaning techniques, including:
    - handling null values by:
        - manually filling nulls with pertinent information from other columns
        - replacing NaNs in age column with column average
        - establishing a threshold to remove observation rows that have too many null values
    - removing duplicates
    - standardizing formats using methods such as
        - .upper() and .lower()
        - .strip()
        - .replace()
    - implement understanding of SQL to standardize date formatting
    - deleting dataframe irrelevant variables and observations, including:
        - removing data about shark attacks that occurred on the high seas, because they are not relevant to our data
        - removing data about shark attacks that happened prior to the year 2014 as being too far out-of-date to be pertinent

## Exploratory Data Analysis
- Utilized EDA techniques to analyze data, validate hypotheses, and draw actionable insights.
  - identified top 5 countries where shark attacks are most common
    - identified countries with highest number of fatalities
    - examined the difference in outcomes of sharks attack (most DO NOT end in fatalities)
    - compared top 5 countries to the rest of the world in regards to fatalities
- Created visually appealing charts and graphs using Python libraries, facilitating decision-making.
