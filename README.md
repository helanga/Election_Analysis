# Election_Analysis

## Overview of Election Audit


## Election-Audit Results
- How many votes were cast in this congressional election?
  
  Total votes cast in this election is 396,711
  
  ![](Resources/images/Total_votes.JPG)
  
 - Breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   - To calculate countywise votes:
     First I created county_options list and county_votes dictionary.
     
     ![](Resources/images/county1.png)
     
    - then condition statement check that the county does not match any existing county in the county list and then add the existing county to county list  of counties and add vote to the county's vote count
     
    
     ![](Resources/images/county2.PNG)
     
     - At last, calculate votes and presentage for each county using for loop
     
     ![](Resources/images/county3.PNG)
     
  - Which county had the largest number of votes?
    - According to the analysis, Denver county has largest number of votes
    - Below is the output for countywise analysis
    
       ![](Resources/images/county_votes.JPG)
       
   - Breakdown of the number of votes and the percentage of the total votes each candidate received.
     
     ![](Resources/images/Candidate_votes.png)
    
    
   - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
      
      - Candidate Diana DeGette won the election.
      
        ![](Resources/images/Winning_CandidateOutput.png) 
        
       - Following part of code will describe how does the script calculate/retreive winning precentage and candidate
       
         ![](Resources/images/Winning_CandidateCode.png)
         
 ## Election-Audit Summary
     
