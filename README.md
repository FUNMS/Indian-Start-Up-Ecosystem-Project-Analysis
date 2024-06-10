Indian-Start-Up-Ecosystem-Project-Analysis
This project aims to explore the Indian startup ecosystem based on data from 2018 to 2021 and propose the best course of action for entering this dynamic market. The analysis leverages datasets covering investment trends, sectoral growth and providing a comprehensive overview to guide strategic decision-making.

Business Objective
The aim of this project is to perform analysis on the Indian start-ups ecosystem and advice stakeholders on which venture to invest in to increase the potential of high profit/income

Data Understanding

Certain assumptions were made regarding company categorizations, and there may bee limitations due to the variations in data retrieval from sources. 
Data was loaded using a combination of python libraries such as pyodbc which was used as connection to an sql database source and pandas to read the csv_files. pandas was also used in the processing of the data.
All the necessary libraries like pandas, numpy, matplotlib, plotly are to be installed. Install pyodbc - a package for creating connection strings to your remote database
Also, install python-dotenv - a package for creating environment variables that will help you hide sensitve configuration informantion such as database credentials and API keys

Process

A.Import all the necessary libraies

B .pyodbc (for creating a connection)

C.python-dotenv (loading environment variables) 

D Now create a file called .env in the root of your project folder (Note, the file name should begin with a dot)

6.In the .env file, put all your sensitive information like server name, database name, username, and password

Hypothesis Testing

Null Hypothesis(Ho): There is no significant difference in the amount of funding between startups in Bangalore.

Alternative Hypothesis(Ha): There is a significant difference in the amount of funding between startups in Bangalore.

Data Structure

'Company_Brand`: Name(s) of the startup (String)
founders: Name(s) of the founder(s) (String)
founded: Year the startup was founded (Datetime)
Sector: Industry sector of the startup (String)
HeadQuarter: City where the startup is based (String)
funding_amount: Total funding received by each startups in US dollars (Float)
Stage: This is the funding stages for each business which ranges from the pre-seed stage to IPO (Integer)
investors: List of investors (String)
funding_year:The year each company got the funding

