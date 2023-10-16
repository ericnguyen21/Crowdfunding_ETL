# Crowdfunding_ETL



##Group 2 Project 2 


## Crowdfunding Campaign Analysis

This repository contains data and analysis for a crowdfunding campaign. The data is stored in CSV files and the analysis is performed using Python and SQL.

## Data

The data for this project is stored in four CSV files exported from the pandas section:

1. `campaign.csv`: Contains data about each crowdfunding campaign.
2. `category.csv`: Contains data about the different categories of campaigns.
3. `contacts.csv`: Contains data about the contacts associated with each campaign.
4. `subcategory.csv`: Contains data about the different subcategories of campaigns.

## Database Schema

The database schema for this project is included in the repo as "crowdfunding_db_schema.sql".
The schema includes four tables corresponding to the four CSV files. The `campaign` table includes foreign keys linking to the `contacts`, `category`, and `subcategory` tables.

## Analysis

The analysis for this project is performed using Python and SQL. The Python code loads the data from the CSV files into pandas dataframes, performs some initial exploration and cleaning of the data, and then saves the cleaned data back to CSV files. The SQL code creates the database schema and performs some queries on the data.


## Contributing

Contributions to this project were made by the three members of group 2, namely Adam Mayer, Thinh Nguyen and Edrin Ngadze with assistance from the teaching staff.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
