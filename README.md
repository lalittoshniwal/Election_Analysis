# Election_Analysis

## Overview of Election Audit:
The purpose of this analysis was to import a CSV file containing election results into Python for analyzing its content for the following:
* determine total ballots casted in this election
* identify which candidate won the election, 
* how many votes and percentage of total votes did each candidate recieve, 
* how many votes were casted in each county and their percentage to total vote count
* which county had the largest turnout

## Election-Audit Results: 
Here are the results of the analysis:
* How many votes were cast in this congressional election?
    - 369,711

    Screenshot of the code:
<img src="/Resources/totalVoteCount.png" >


* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    County Votes:
    Jefferson: 10.5% (38855)
    Denver: 82.8% (306055)
    Arapahoe: 6.7% (24801)


    Screenshot of the code:
<img src="/Resources/countyVoteCount.png" >

* Which county had the largest number of votes?
    - Denver

        Screenshot of the code:
<img src="/Resources/largestCounty.png" >


* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)

        Screenshot of the code:
<img src="/Resources/candidateVoteCount.png" >


* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%

    Screenshot of the code:
<img src="/Resources/winningCandidate.png" >


## Election-Audit Summary: 
The script provided here is very versatile and can be applied to any election with small modifications. For example: if the state rules require run-off election or automatic recount instead of declaring a winner by popular for tight races, the script can be updated with a conditional statement to check for the lead margin before declaring an election winner. If the data is available, we can easily categorize the ballots casted by various methods i.e. mail-in vs. in-person etc., and tabulate the results accordingly.


