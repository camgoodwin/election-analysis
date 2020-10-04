# election-analysis
# Overview of Election Audit
The purpose of this election audit was to obtain all the important data aspects to submit to the election commission.  They wanted to know how many votes were casted in this election, the county with the largest number of votes, and multiple percentage breakdowns in order to create a clearer picture. 
# Election-Audit Results
* How many votes were cast in this congressional election? 
  * In this congressional election there were 369,711 votes that were cast.  
* Which county had the largest number of votes?
  * Denver was the county with the largest number of votes that totaled to 306,055
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  * Charles Casper Stockham recieved 85,213 votes, which is 23.0% of the total votes.   
  * Diana DeGette received 272,892 votes, which is 73.8% of the total votes.   
  * Raymon Anthony Doane received 11,606 votes, which is 3.1% of the total votes. 
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * Diana DeGette won the election with 272,892 votes meaning that she won over 73.8% of voters. 
# Election-Audit Summary
The election commission should review future elections in the same way that was provided within this analysis.  There would be certain changes that would need to be made to the code for each election, however it will provide the essential information. 
1. We can use the following code, however we would need to change the county name. Here it is listed as Jefferson and we would need to change that for future elections.
 i. if county_name == "Jefferson":
            ii. num_county_Jefferson += 1
2. Also, since there were only a few counties in this election I did list them as below.  If there were more counties involved that were difficult to count I would need to change the code in order for it to know the counties without having to list them. 
 i. county_list = ["Jefferson", "Denver", "Arapahoe"]   
        
