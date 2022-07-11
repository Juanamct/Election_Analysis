# Election_Analysis: Totaling election results using Python
## Task:
A Colorado Board of Elections employee tasked me with the following to complete the election audit of a recent, local, congressional election.

## Requirements:
  1. Calculate the total number of votes cast.
  2. Provide the number of votes and percentage of total votes for each county in the precinct.
  3. Determine the counth that had the largest number of votes.
  4. Get a complete list of candidates who received votes.
  5. Calculate the total number of votes each candidate received.
  6. Calculate the percentage of votes each candidate won.
  7. Determine the winner of the election based on popular vote.
  
 ## Resources
  - Data Source: election_results.csv
  - Sortware: Python 3.6.7, VS Code, 1.69.0
  
 ## Results Summary
  The Analysis of the election is as follows:
    - Total # of Votes cast in the election were 369,711
    - The individual county vote results were:
      * Jefferson: 10.5% (38,855)
      * Denver: 82.8% (306,055)
      * Arapahoe: 6.7% (24,801)
      
    - The county with the largest turnout
      * Denver
      
    - The candidates were:
      * Charles Casper Stockham
      * Diana DeGette
      * Raymon Anthony Doane
      
    - The individual candidate results were:
      * Charles Casper Stockham received 23.0% of the vote with 85,213 votes
      * Diana DeGette received 73.8% of the vote with 272,892 votes
      * Raymon Anthony Doane received 3.1% of the vote with 11,606 votes
      
     - The Winner of the election was:
      * Diana DeGette who received 73.8% of the vote with 272,892 votes
      
 ## Challenge Overview
  The election commission has requested county voting detail and summary added along to the canditate voting summary.
     - Requested county detail:
      * The voter turnout for each county
      * The percentage of votes from each county out of the total count
      * The county with the highest turnout
     
     - Using repetition statements, conditional statement with logical operators, and print statements much like those used for        the candidate detail and summary.
     
 ## Challenge Summary
  This script could be quickly modified to be used for any election by:
   1. uploading the county voting results in a csv file and adjusting the file path to load (file_to_load)
   2. updating the column header location references according to the column on the csv file
   
      
      
