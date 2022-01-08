# Election_Analysis Project Overview:

The purpose of this project was to determine election results for 3 counties in Colorado. The tasks were:
1. Determine total votes
2. Create a list of candidates and counties
3. Tabulate votes each candidate received and count of votes cast in each county
5. Calculate percent that each candiates won and the percent of votes that came from each county
6. Declare the winner of the election and the county with the highest voter turnout

# Data Sources:
election_results.csv
See Resources folder


# Election Audit Results
* There were 369,711 votes cast in this election
* County votes and percentages are as follows:
* County Votes:
    * Jefferson: 10.5% (38,855)
    * Denver: 82.8% (306,055)
    * Arapahoe: 6.7% (24,801)
* Denver County had the highest voter turnout


* Candidate votes:
    * Charles Casper Stockham: 23.0% (85,213)
    * Diana DeGette: 73.8% (272,892)
    * Raymon Anthony Doane: 3.1% (11,606)

The winnter of the election is:
Diana DeGette with 73.8% of the votes, and 272,892 total votes

# Election Audit Summary
This script is easily adaptable to many different election. It can be used with csv files as long as there is a geo area column and a candidate column

For future elections this script can be modified in the following ways:
1. For an election with more than 3 candidates the good news is this script does not need to be changed at all!
    * because it is written with aggregating candidates/counties as lists and not pre-defined counts it will work with different numbers of geos/candidates
3. If the votes data csv column headers are in a different order the column indexes will need to be changed.<img width="239" alt="ModExample1" src="https://user-images.githubusercontent.com/95047485/148663490-247b163b-8f0f-4821-9b5f-86b869735c58.PNG">
4. If the margins in the election are very close and the winning percentages need more decimal places that can easily be changed in the following printout:<img width="328" alt="ModExample2" src="https://user-images.githubusercontent.com/95047485/148663514-94c2affa-ba35-4631-96fe-8f60e1ebf592.PNG">



