# This folder consists of Data Analysis and Manipulation projects using Python Pandas

## Legacy reward products/inactive customers cleanup from loyalty program partner database
### Context :
The loyalty program partner provide variety of products/offerings/flexible redemptions to it's client(Bank) and customers/employees of the Bank. Benefits include redemptions that fit everyone’s needs, which in turn help in employee /customer retention with the Bank. However, all this comes with a cost to the Bank and Bank is charged for every single customer in the partner database. 

### Dataset Description :
 - Credit card customers database in csv
 - Reward points available for credit card customers (rewards vendor database) in csv
 
Note : As per the PCI compliance, Bank's do not share the customer data and make it available to public, hence the datasets used in this analysis are dummy datasets and do not contain actual customer data. Also, as the datasets are large in size , the data used here is having limited data with just 500 customers data in excel.

### Objective :
1. Load and examine/subset columns for each individual dataset
2. Aim is to Reduce the cost by identifying the inactive/legacy/not eligible credit cards in the Bank's loyalty program partner database.
3. Combine them into a single dataset and export it back to csv.


## Exploring Data (Manipulation) of National Basketball Association (NBA) games from 2004 to 2020
### Context:
- The data is about NBA (National Basketball Association) games from 2004 season to Dec, 2020.
- Focusses on importing data and data manipulation techniques.
- Original source (https://www.kaggle.com/nathanlauga/nba-games).
- Dataset has been slightly modified.

### Dataset Description:
Two datasets (in two separate csv files):

games: each game from 2004 season to Dec 2020, including information about the two teams in each game, and some details like number of points, etc
teams: information about each team played in the games

Assume we want to study the game level data, but with detailed information about each team. We'll need to combine these two datasets together.

### Objective:
1. Load/examine/subset/rename/change dtypes of columns for each individual dataset
2. Combine them into a single dataset, and export it
3. Explore the final dataset by subsetting or sorting
