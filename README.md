# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of the recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the total number of votes each county received.
7. Calculate the percentage of votes each county received.
8. Determine the county with the highest number of votes.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.12, Visual Studio Code, 1.69.0
   
 ## Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- County votes:
    - The counties were:
        - Arapahoe County
        - Denver County
        - Jefferson County
    - The county results were:
        - Arapahoe County received 6.7% of the vote and 24,801 total votes.
        - Denvery County received 82.8% of the vote and 306,055 total votes.
        - Jefferson County received 10.5% of the vote and 38,855 total votes.
    - The winner of the election was:
        - Denver County, who received 82.8% of the vote and 306,055 total votes. 
- Candidate votes:
    - The candidates were:
        - Charles Casper Stockham
        - Diana DeGette
        - Raymon Anthony Doane
    - The candidate results were:
        - Charles Casper Stockham received 23.0% of the vote and 85,213 total votes.
        - Diana DeGette received 73.8% of the vote and 272,892 total votes.
        - Raymon Anthony Doane received 3.1% of the vote and 11,606 total votes.
    - The winner of the election was:
        - Diana Degette, who received 73.8% of the vote and 272,892 total votes.

 ## Challenge Summary

This code can be used with any election by making a couple modifications as outlined below.
- One way this code can be modified to use with any election is by changing the text output from "County" to the type of election you are running the code for, for example, "District".   
    - Original code:
        
        ![Code Screenshot County 1](/Resources/Code_Screenshot_County1.png)   ![Code Screenshot County 2](/Resources/Code_Screenshot_County2.png)
    - Revised code:
        
        ![Code Screenshot District 1](/Resources/Code_Screenshot_District1.png)  ![Code Screenshot District 2](/Resources/Code_Screenshot_District2.png)
    - Revised output:
        
        ![Results Screenshot District](/Resources/Results_Screenshot_District.png)
- Another modification that might need to be made is changing where the code is pulling the data from and where the results are written to.
    - Lines of code to update:
    
    ![Code Screenshot](/Resources/Code_Screenshot.png)
