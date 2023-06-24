# PYTHON - PyBank & PyPoll Analysis

It's time to put away the Excel sheet and enter the world of programming with Python. In this assignment, I'll use the concepts I've learned to complete two Python challenges, PyBank and PyPoll. Both tasks present a real-world situation where my newly developed Python scripting skills come in handy.

## Before I Begin

Before starting the assignment, I will complete the following steps:

* Create a new repository for this project called python-challenge. I will not add this homework assignment to an existing repository.

* Clone the new repository to your computer.

* Inside my local Git repository, create a folder for each Python assignment and name them PyBank and PyPoll.

* In each folder that I just created, add the following content:
   •	A new file called main.py. This will be the main script to run for each analysis.
   •	A Resources folder that contains the CSV files I used. Make sure that My script has the correct path to the CSV file.
   •	An analysis folder that contains my text file that has the results from my analysis.

* Push these changes to GitHub or GitLab.


### PyBank Instructions

In this Challenge, I am tasked with creating a Python script to analyze the financial records of my company. I will be given a financial dataset called budget_data.csv. The dataset is composed of two columns: "Date" and "Profit/Losses".

* My task is to create a Python script that analyzes the records to calculate each of the following values:

   •	The total number of months included in the dataset
   •	The net total amount of "Profit/Losses" over the entire period
   •	The changes in "Profit/Losses" over the entire period, and then the average of those changes
   •	The greatest increase in profits (date and amount) over the entire period
   •	The greatest decrease in profits (date and amount) over the entire period


* My analysis should align with the following results:

Financial Analysis
----------------------------
Total Months: 86
Total: $22564198
Average Change: $-8311.11
Greatest Increase in Profits: Aug-16 ($1862002)
Greatest Decrease in Profits: Feb-14 ($-1825558)

* In addition, my final script should both print the analysis to the terminal and export a text file with the results.


#### PyPoll Instructions

In this Challenge, I am tasked with helping a small, rural town modernize its vote-counting process.

* I will be given a set of poll data called election_data.csv. The dataset is composed of three columns: "Voter ID", "County", and "Candidate". My task is to create a
  Python script that analyzes the votes and calculates each of the following values:
   •	The total number of votes cast
   •	A complete list of candidates who received votes
   •	The percentage of votes each candidate won
   •	The total number of votes each candidate won
   •	The winner of the election based on popular vote

* My analysis should align with the following results:

Election Results
-------------------------
Total Votes: 369711
-------------------------
Charles Casper Stockham: 23.049% (85213)
Diana DeGette: 73.812% (272892)
Raymon Anthony Doane: 3.139% (11606)
-------------------------
Winner: Diana DeGette
-------------------------

* In addition, my final script should both print the analysis to the terminal and export a text file with the results.


##### Hints and Considerations

* Consider what I've learned so far. I've learned how to import modules like csv. I've learned how to read and write files in various formats. I've learned 
  how to store content in variables, lists, and dictionaries. I've learned how to iterate through basic data structures. And I've learned how to debug along the way. Using all that I've learned, try to break down my tasks into discrete mini-objectives.

* The datasets for these Challenges are quite large. This was done purposefully to showcase one of the limits of Excel-based analysis. As data analysts, our first
  instinct is often to go straight to Excel, but creating scripts in Python can provide us with more powerful options for handling big data.

* Write one script for each of the provided datasets. Run each script separately to make sure that the code works for its respective dataset.

* Always commit my work and back it up with pushes to GitHub or GitLab. I don't want to lose hours of my hard work! Also make sure that my repo has a detailed README.md file.


---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.