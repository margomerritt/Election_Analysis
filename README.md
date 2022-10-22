# Election Audit
## Overview of Election Audit
### Purpose
The purpose of this project is to tabulate the results for a U.S. congressional precinct in Colorado. The goal is to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner based on the popular vote. The election dataset was provided in a .csv format. This dateset was imported into VS code using Python to do the data analysis. 

In the dataset there are three columns of data: Ballot ID, County, and Candidate. The three counties in this congressional election are Jefferson, Denver, and Arapahoe. The three congressional candidates are Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. There are 369,711 rows of entries in the dataset. Each row indicates a singular vote. 

### Resources
* Data Source: election_results.csv
* Software: Python 3.9.12, Visual Studio Code 1.72.1

## Election-Audit Results

The analysis of the election shows that:
* There were 369,711 total votes cast in this congressional election. This vote count includes all votes cast in all three counties for the three candidates running. 
 
![total_votes](https://user-images.githubusercontent.com/111299372/197276268-1d2ca1e3-3adb-48fc-9854-41b6d39e0528.png)

* The county results were:
	- Jefferson county received 10.5% of the total votes and 38,855 votes.
	- Denver county received 82.8% of the total votes and 306,055 votes.
	- Arapahoe county received 6.7% of the total votes and 24,801 votes.

![votes_per_county](https://user-images.githubusercontent.com/111299372/197276287-d43e88d9-fd82-4244-bee1-e4060e74c675.png)

* Denver had the largest number of votes with a total of 306,055 votes cast in its county. 

![largest_county_turnout](https://user-images.githubusercontent.com/111299372/197276306-b4532e58-e4e5-49af-a029-6684d65b8ad5.png)

* The candidate results were:
	- Charles Casper Stockham received 23.0% of the total votes and 85,213 votes.
	- Diana DeGette received 73.8% of the total votes and 272,892 votes.
	- Raymon Anthony Doane received 3.1% of the total votes and 11,606 votes.

![individual_votes_cast](https://user-images.githubusercontent.com/111299372/197276319-a70eb712-763f-4d43-b9f3-d504bd6476a7.png)

* The winner of the congressional election was: 
	- Diana DeGette, who received 73.8% of the vote and 272,892 votes.

![election_winner](https://user-images.githubusercontent.com/111299372/197276334-578eb0bd-b439-4c6f-9f54-a5c620391c22.png)

		

## Election-Audit Summary
The Python script written for this project can be modified to use for any election. This script was written for the Colorado board of elections to use it for a congressional election for the district made up of the counties Denver, Jefferson, and Arapahoe. The script could be easily modified to be used for the other remaining congressional districts in Colorado by simply importing a dataset with the counties and candidates for the new district. This script could also be used for senatorial districts and local elections with a few modifications as well. 

This is a useful script to modify and use for any election. This script outputs the overall winner, but also calculates a lot of other useful data as well such as the overall vote count for each county. All this data can by analyzed to ensure the integrity of the election. For example, in this project there were 24,801 votes cast in Arapahoe county. If Arapahoe only had 20,000 registered voters then the election committee would know that there were illegal votes cast at the Araphaoe precincts. This would give the Colorado Elections board the opportunity to initiate a recount and potentially prevent voter fraud for future elections.
