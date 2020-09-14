# Election_Analysis

## Overview of Election_Audit
A Colorado Board of Election employee has given the following tasks to complete the election audit of a recent local congressional election.
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the percentage of votes each candidate won.
4. Determine the winner of the election based on popular votes.

The election commission has requested some additional data to complete the audit:
5. The voter turnout for each county
6. The percentage of votes from each county out of the total count
7. The county with the highest turnout


## Resources
- Data Source: election_results.csv
- Software: Python 3.8.3, Visual Studio Code, 3.1.3

## Election_Audit Results:
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were :
    - Candidate Charles Casper Stockham 
    - Candidate Diana DeGette
    - Candidate Raymon Anthony Doane
- The candidate results were:
    - Candidate Charles Casper Stockham received "23.0"% of the vote and "85,213" number of votes.
    - Candidate Diana DeGette received "73.8"% of the vote and "272,892" number of votes.
    - Candidate Raymon Anthony Doane received " 3.1"% of the vote and "11,606" number of votes.
- The winner of the election was:
    - Candidate Diana DeGette who received "73.8"% of the vote and "272,892" number of votes.
- The counties were :   
    - County Jefferson
    - County Denver
    - County Arapahoe
- The county results were:
    - County Jefferson received "10.5"% of the vote and "38,855" number of votes.
    - County Denver received "82.8"% of the vote and "306,055" number of votes.
    - County Arapahoe received " 6.7"% of the vote and "24,801" number of votes.
- The largest county turnout was:
    - County Denver which received "82.8"% of the vote and "306,055" number of votes.
    
![Terminal result:](Election_Analysis/Terminal_result.png)
![election analysistxt:](Election_Analysis/election_analysistxt.png)

## Election_Audit Summary
The scrip of Election_Audit can be used for any other election as we created list and dictionary for each row of vote details, candidates and counties.
with any other csv.file we can use this scrip with a little change in index number or printed texts.
