# Election_analysis
Python Module 3
## Overview
---
### This dataset contains the ballot ID, County name, and Canditate name. There are 3 counties: Jefferson, Denver, and Arapahoe. There are also three canditates: Charles Casper Stockham, Diana DeGette, and Raymon Anythony Doane. The purpose of this analysis is to determine which county had the largest number of ballot votes, as well as the candidate with the largest number of ballot votes. With this dataset, we will determine which candidate won the election, based of total counts and percentages. Additionally, we will determine how many votes each county had, as well as the percentage of votes from each county. With the use of python, we will run analysis on this data to determine the election results. We will create lists, dictionaries, for loops, common operators, decision statements, and then print the results. By reading in the election results csv, we will be able to manipulate the dataset to print in a way that makes sense to us and the general public to clearly see who the winner of the election is.
----
## Results
---
### After running the analysis, we have received an output text file which can be seen below. With this text file, we are able to state total votes, county votes, candidate votes, as well as overall percentages. The analysis results can be find below, both the text file and terminal output, which is then followed by bullet points summarizing the election results.
---
![image](https://user-images.githubusercontent.com/119131202/209231492-d5258e17-e4d6-45d9-9db5-a2da8f49fddc.png)
![image](https://user-images.githubusercontent.com/119131202/209234391-df9e0bdc-b4fe-4b4c-ad9d-0fba7d93221d.png)

---
* There was a total 369,711 votes in this election.
---
---
* The Jefferson county had a total of 38,855 votes, which is 10.5% of the total votes. Denver has 306,055 votes, which is 82.8% of the total votes. Lastly, the county Arapahoe had 24,801 votes, which is only 6.7% of the total votes.
---
* Denver had the largest number of votes, with 306,055 votes resulting in nearly 83% of the total number of votes.
---
### The image below shows the code of how we got the counts and percentages of all counties. There was a for loop created to loop through all the data to get the county vote count and percentage, which is then printed to the terminal and added to a text file when prompted to do so.
---
![image](https://user-images.githubusercontent.com/119131202/209233411-969c8158-9e07-45d3-94e9-6c9f905e9a86.png)
---
* Charles Casper Stockhom had 85,213 votoes, which is exactly 23% of the total number of votes in this election. Diana DeGette had 272,892 votes, which is 73.8% of the total votes. Raymon Anythong Doane had 11,606 votes, leaving him with only 3.1% of the votes.
---
* With the majority of votes: 272,892 (73.8), Diana DeGette is the winning candidate for this election.
---
### The code for both the candidates counts and percentages can be found below. This code includes the statement of the winning candidate, where the winning candidate secured the majority of the votes.
---
![image](https://user-images.githubusercontent.com/119131202/209234221-c7399ab8-8fae-4a76-af98-f7c24f54e370.png)
---

## Summary
---
### This data examines a simple csv file containing the votes for this specific election, however, this code can be manipulated in a way where it could work for any future elections with different counties and candidates. This code can read a different set of election results (if columns are the same) by just changing the path of where the new dataset is being loaded. This line of code can be found in the very beginning of the code on line 9 (see image). 
---
![image](https://user-images.githubusercontent.com/119131202/209235483-2669c3f9-4efd-4ba0-983b-16d8accc2030.png)

### By reading in the apporiate election data (csv file), the code will create a list of the counties and candidates in the data set and begin to start counting votes. New counties and candidates will be "appended" to the lists. Another example of how this code could be modified is by adding additional data to the csv, say for example States. The code can add a new variable that counts the total number of votes and percentages of each state. The rest of the code will run the analysis as normal and print out the count of percentage of each county (and state for this example) and candidate like we just witnessed with the original dataset.
---
#### Analysis Performed by Katelin Catton
12/22/2022
