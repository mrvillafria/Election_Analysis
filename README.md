# PyPoll with Python

## Overview of Project
For this week's project, we are using Python to generate an election vote count report. Python is a very powerful and popular programming language that we will use to read, write, process, and manipulate data. There are several ways that we can write and execute Python scripts such as through the Python interpreter or using a text editor. For this project, the text editor we will be using is Visual Studio Code.

### Purpose
The purpose of this project was to assist a Colorado Board of Election employee, Tom. Tom is asking us to tabulate election results and create a report for a U.S. Congressional precinct in Colorado. There are three primary voting methods in this data set that we're considering: mail in ballots, punch cards, and direct recording electronic. Not only can this code be used for this specific scenario, but we're hoping it will be utilized for other congressional districts, senatorial districts, and location elections. Using this data, we will report number of total votes, each county's number of votes and percentage of total votes, the county with the largest number of votes, each candidate's number of votes and percentage of total votes, and the winning candidate with their vote count and percentage of total votes.

## Election Audit Results

Our data set consisted of three fields in a CSV file: Ballot ID, County, and Candidate. First, we imported our dependencies to help us open and read CSV files as well as interact with our operating system. The OS and CSV modules are prewritten programs that have specific functions and methods readily available to use. We first loaded the CSV file and then used different conditionals and loop statements to count the total votes, each county's votes, and each candidate's votes. Based on these numbers, we were then able to calculate the percentage for each of these vote counts. After these numbers were calculated, we were able to determine the winner of the election. These results were then printed to the terminal as well as written to a text file. 

#### Election Results
- Total number of votes: 369,711
- Each county's total vote count
	- Jefferson: 38,855
	- Denver: 306,055
	- Arapahoe: 24,801
- Each county's percentage of total votes
	- Jefferson: 10.5%
	- Denver: 82.8%
	- Arapahoe: 6.7%
- County with the largest number of voters: Denver
- Each candidate's total number of votes
	- Charles Casper Stockham: 85,213
	- Diana DeGette: 272,892
	- Raymon Anthony Doane: 11,606
- Each candidate's percentage of total votes
	- Charles Casper Stockham: 23.0%
	- Diana DeGette: 73.8%
	- Raymon Anthony Doane: 3.1%
- Winner of the election: Diana DeGette
- Winning vote count: 272,892
- Winning percentage of total votes: 73.8%

Here is a screenshot of the results when the code is ran from the terminal:

![election_results_terminal](/Resources/election_results_terminal.PNG)

[Election Analysis Text File - Link](https://github.com/mrvillafria/election_analysis/blob/main/analysis/election_analysis.txt)

## Election Audit Summary
Based on the results we generated, we believe this report would be helpful for other congressional districts, senatorial districts, local elections, or any election. The information in our report provides insightful information in a concise way. We feel it is important to not only show the number of votes, but the percentage is also valuable as well. A few modifications that could be made, depending on if the data was available, would be to adjust the location criteria based on what type of election was being conducted. For example, in this case, we are only looking at county votes, but perhaps could look at a city or state vote counts instead. After last year's presidential election, there was a lot of controversy around the submission of votes. We could also report on the different voting methods if that data was available to show the number of votes that were mail-in, punch card, or direct recording election (DRE). 