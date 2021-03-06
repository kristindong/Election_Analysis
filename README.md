# Election_Analysis

## Overview of Election Audit
The purpose of this project is to help the Colorado Board of Election perform an audit on a recent local congressional election. The audit is performed by using Python script to analyze an election results data set containg county name and candidate name for each vote cast. The data is stored in a csv file. The analysis consisted of the following tasks:

1. Calculate the total number of votes cast
2. Calculate the number of votes cast in each county in the precinct
3. Determine the county with the largest voter turnout
4. Calculate the number of votes and percentage of votes each candidate received
5. Determine the winner of the election based on popular vote

## Resources
- Data Source: election_results.csv 
  https://github.com/kristindong/Election_Analysis/blob/4c7f05a4710c51b1c07ac23febef6c424507e598/Resources/election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.65.2 

## Election Audit Outcome

Results of the election audit are summarized below.

* Total Votes Cast: 369,711

* Votes by County:
  * Jefferson:  10.5% (38,855)
  * Denver:  82.8% (306,055)
  * Arapahoe:  6.7% (24,801)

* Largest County Turnout: Denver

* Votes by Candidate:
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)

* Election Outcome:
  * Winner: Diana DeGette
  * Winning Vote Count: 272,892
  * Winning Percentage: 73.8%


A sample of the script and results displayed in Visual Studio Code:

![VSCode_screenshot](VSCode_screenshot.png)

The text file containing the audit results is saved here:
https://github.com/kristindong/Election_Analysis/blob/50a03a50484d6af8364f489912598d382ab73a71/analysis/election_analysis.txt


## Election Audit Summary
With some modifications, the Python script used for this election audit can be used for any election, provided that the data is stored in csv format and contain county and candidate name for each vote cast. 

1. The name and path of the election results csv file and election analysis text file may need to be modified if the file name and location are not the same as those used in the code.

![Code_Modification_1](Code_Modification_1.png)


2. If county and candidate name are not in columns 2 and 3, respectively, the the index values in the code below will need to be adjusted to reflect the columns they are stored in the data file. 

![Code_Modification_2](Code_Modification_2.png)
