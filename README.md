<<<<<<< HEAD
# Election_Analysis

## Project Overview
A Colorodo Board of Elections employee has given us the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total count.
8. Determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.71.0

## Results
- A total of 369,711 votes were cast in this election
- The votes per county were:
    - Jefferson County had 38,855 votes for 10.5% of the total votes.
    - Denver County had 306,055 votes for 82.8% of the total votes.
    - Arapahoe County had 24,801 votes for 6.7% of the total votes.
- Denver County had the largest number of votes (306,055)?
- Below is a breakdown of the percentage of votes and total votes received by each candidate.
    Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 total votes.
- Below is a screenshot of the terminal after running the audit script.
exclamation mark(github path to Terminal_Output_Screenshot)

# Summary
The script for this audit read the raw election data, then organized and tallied vote counts per candidate and county. Its modular format allows for modification to fit other types of elections. For example, in the following code:
```
county_count = county_votes.get(county_name)
```
the county variables could be changed to precinct variables to suit city and county elections as follows:
```
precinct_count = precinct_votes.get(precinct_name)
```
Likewise for referendum and recall elections, candidate variables...
```
candidate_options = []
candidate_votes = {}
```
could be modified to reflect Yes/No options
```
yes_votes[yes_option] += 1
```
=======
# Election Analysis

## 
>>>>>>> 51ca43b2cc3ffc210f2f95c9ad47bf7d5a914a40
