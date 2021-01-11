# Election_Analysis

## Overview of Election Audit: 
The purpose of this election analysis is to write a code that is able to sort through the list of votes in a Colorado election. With this program, we should be able to tally the numnber of votes that each candidate received from each of three different counties, Arapahoe, Denver, and Jefferson counties. The program is then able to calculate the differnt percentag of votes that each candidate received in terms of the total votes, as well as the county that had the highest voter turnout percentage.

## Election-Audit Results: 
### - How many votes were cast in this congressional election?
  
  369,711 votes were cast in this congressional election. See iamge below.
  
  ![total_votes_txt.png](/total_votes_txt.png)

### - Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  
  The breakdown of number of votes by county are as follows. Jefferson county received 38,855
  votes, which is 10.5% of the total votes in the election. Denver county received 306,055 votes,
  which equates to 82.8% of the total votes in the election. The remaining 24,801 votes went to
  Arapahoe county, which received the lowest percentage of voter turn out at 6.7%. See image below
  for what is written in the *election_analysis.txt* file when the program is executed.
  
  ![county_results_txt.png](/county_results_txt.png)
  
### - Which county had the largest number of votes?
  
  The county with the largest number of votes is Denver. Denver received 306,055 votes, which
  represents 82.8% of the total vote count. The image above illustrates the text file output fo
  the county with the largest turnout.
  
### - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  
  There were a total of three candidates running in the election, Charles Casper Stockham, Diana
  DeGette, and Raymon Anthony Doane. Charles Casper Stockham received 85,213 votes, making up 23%
  of the total votes. Diana DeGette received 272,892 votes, making up 73.8% of the total votes.
  Lastly, Raymon Anthony Doane received 11,606 votes, making up 3.1% of the total votes cast in
  the election. See image below for a breakdown of the votes by candidate and the winning
  candidate result.
  
  ![candidate_results_txt.png](/candidate_results_txt.png)
  
### - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

  The candidate that won the election is Diana DeGette. She received 272,892 votes, which makes up
  73.8% of the total vote cast in the election. The image above shows the output on the text file
  when the program is run and the text file is written into.

## Election-Audit Summary:

Dear election commission, I am confident that this script can be used to tally votes for any
election. We would need an updated csv file with the total votes for each candidate, along with the county each vote came from. If you wanted to go up in scale, you could even go state by state in the US, for example, as long as you have a csv file with a similar format that you can create a path to open the .csv file and write the results on the *election_analysis.txt* file, it should run fine. Another modification that could be done to the script so that it can be applied to any election is that if we wanted to go in a bigger scale, for example, if we wanted to look at election resuls by state in addition to the county, we could put the state on the next row of the csv file and would need to add a line of code that extracts the state name from each row in the .csv file. the code line would look something like:

  state = row[3]
  
 The 3 after "row" would signfy the column that the lists each of the states on each row. We would
 then need to add an if-statement iniside the for loop to show have the program add each state on
 the text file as it finds a new state and reads it in the .csv file.



