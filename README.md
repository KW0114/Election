# Election Analysis

## Overview
     This analysis was performed on a dataset of ballots from three different counties:
Arapahoe, Denver, and Jefferson. 
Our job was to decide the winner of the election, as well as determine the county
with the highest voter turnout.

## Results

* In total, there were 369,711 votes cast in this election. 

* Arapahoe accounted for 24,801 votes, which was 6.7% of all votes.
* Denver accounted for 306,055 votes, which was 82.8% of all votes.
* Jefferson accounted for 38,855 votes, which was 10.5% of all votes.

* Denver had the largest voter turnout by a landlside. 

There were 3 candidates: Charles Stockham, Diana DeGette, and Raymon Doane:
* Stockham acquired 23% of votes (85,213)
* DeGette acquired 73.8% of votes (272,892)
* Doane acquired 3.1% of votes (11,606)

* The obvious winner for this election was Diana DeGette. As stated above, she got
73.8% of the total vote (272,892).

See the output of this election analysis that recaps all this information:
![election results](https://github.com/KW0114/election-analysis/blob/68e3ac155e204d95ad0e2bcd59020a86fcadbfed/Resources/Election%20Results%20Snapshot.png)

## Summary
     This python script could easily be used for another election, with as many candidates or counties as you would like. 
As these numbers get larger though, it may be best not to print every single candidate and county name to 
the screen or our output file. We could easily change this by making sure we specify only to print maybe
the top 5 candidates, or however many you would be interested in. I would probably do this by creating a separate
list containing the name of the candidates with the highest votes per your specifications. 

     As we get more sophisticated data, we may even be able to add some more values to our analysis, such as age of
voters and how that relates to who they voted for. Maybe we could make a dictionary keeping track of the most popular
candidate for a specific set of age ranges. 
