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
     
     - At last retreive county vote count and precentage of votes for the county used for loop
     
     ![](Resources/images/county3.PNG)
     
  - Which county had the largest number of votes?
    According to the this Analysis Denver county got largest number of votes
    following is the output I received for countywise analysis
    
    ![](Resources/images/county_votes.png)
     
