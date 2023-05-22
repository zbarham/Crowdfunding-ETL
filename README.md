# Crowdfunding-ETL

This repository contains the code and data files for the Crowdfunding ETL (Extract, Transform, Load) project. The project focuses on extracting and transforming data from CSV files containing information about project backers, and performing data analysis using SQL queries.

## Project Deliverables

The project includes the following deliverables:

1. **Extract Data:** The backers' contact information is extracted from the backer_info.csv file using Python and Pandas using the Python dictionary method.

2. **Transform and Clean Data:** The extracted data is transformed and cleaned using Python and Pandas. The cf_id column is converted to the int64 data type, the name column is split into first and last names, and the columns are reordered.

3. **Create an ERD and Table Schema, and Load Data:** An Entity-Relationship Diagram (ERD) and table schema are created based on the data. The backers table is created in the crowdfunding_db database, and the backers.csv file is loaded into the table.

4. **SQL Analysis:** SQL queries are written to perform data analysis on the crowdfunding_db database. The queries retrieve information about backer counts, remaining goal amounts, and other relevant data.
