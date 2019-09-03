# Starbucks Capstone Challenge
by Dave Engelhardt

## Libraries
The following Python libraries were used in this project:
- pandas
- numpy
- math
- json
- matplotlib.pyplot

## Motivation
The motivation behind this project is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.  This will be done by determining the top 5 demographic segments for each offer type (buy-one get-one, discount, and informational).  Demographics are organized based on gender, age segment, and income range segment.

## Files
The files used in the project are as follows:
- Starbucks_Capstone_notebook.ipynb: Jupyter Notebook that explores, cleans, and analyzes the data
- data/portfolio.json: Contains Starbucks offer ids and meta data about each offer (duration, type, etc.)
- data/profile.json: Contains demographic data for each customer
- data/transcaript.json: Records for transactions, offers received, offers viewed, and offers completed

## Results Summary
The data analysis indicates that middle-aged to early senior women with an income of between 70,000 and 80,000 dollars are the best responding demographic overall.  Middle-aged men with a similar income respond well specifically to informational offers.

## Acknowledgements
The Stack Overflow link below was used to help perform one of the tasks in cleaning the data.
https://stackoverflow.com/questions/27506367/python-pandas-integer-yyyymmdd-to-datetime