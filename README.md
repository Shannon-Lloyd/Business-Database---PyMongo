# NoSQL Challenge 
Assignment for UT Data Analysis and Visulization Bootcamp to pratice using PyMongo NoSql. 

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About
Connect to a database, query and update the database.

## Getting Started
All necessary files are located in this nosql-challenge repository.\

The Resources folder contains establishments.json which is the collection for the uk_food database. \
This must be imported first! Git bash into the Resources folder and enter the following command.

`mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`

There are two Jupyter Notebooks to run in the nosql-challenge repository. \
NoSQL_setup.ipynb sets up the database and makes the requested changes to the database, verifying changes as they are made.\
NoSQL_analysis.ipynb preforms various queries to the databse to extract information to be used for analysis.





## Installing
This was generated using jupyter lab on a Windows 10 Pro system.


## Usage
Open GitBash in the Resources folder and run the following command. \
`mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`

Run NoSQL_setup.ipynb in jupyter lab. \
Run NoSQL_analysis.ipynb in jupyter lab.


## Contributing
Thank you to CG:AF at Central Grading for refering me to https://community.codenewbie.org/kwing25/how-to-write-a-good-readme-for-your-project-16ej. I have used this as a template instead of the template from the Gitlab repository for class. Hopefully y'all like it better.\

The materials for class lectures were my biggest references.\


The following websites were helpful for syntax or understanding how things worked. \
https://www.geeksforgeeks.org/  \
https://stackoverflow.com/  \
https://www.mongodb.com/  \
https://pymongo.readthedocs.io/en/stable/index.html  



