# Election_Analysis

##Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 

##Resources 
- Data Source. election_results.csv 
- Software: Python 3.9.5, Visual Studio Code, 1.52.1 

##Summary 
The analysis of the election show that: 
- There were "369,711" votes cast in the election. 
- The candidates were: 
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockham received 23% of the vote and 85,213 number of votes. 
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 
The winner of the election was: 
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 
  
##Challenge Overview

The first steps to this Challenge were to import and inspect the data, which were contained in a CSV file. Next, we reviewed the tasks that needed to be completed and they are outlined above in "Project Overview." We used psuedocode to create a flowchart for our coding. In order to begin to analyze the data, I had to learn how to read a CSV file and write to a text file using Python. The "reader" function was used to read the file, and we printed out headers for the file to begin to sort through the rows. Next, we iterated through each row and gathered data, using the "for" loop to programmatically count up all the votes cast in the election. To count up all the votes, we intialized an "accumulator" variable, and to retrieve the names of the candidates, used indexing on the "for" loop varable, "row." In order to get the unique candidate names, we used an "if" statement with the "not in" membership operator to check if candidate had been added to the list. In order to link the candidates to the votes cast, a dictionary was created where the key is each candidate's name and the vote count for that candidate is the value for the key. This created an output that was each candidate's name as the key and the candidate's vote count as the value. To add votes, we used the Python format for incrementing variables to increment each time a candidate name appeared while iterating through each row. A "for" loop was used to retrieve the votes for each candidate and get the percentage of votes, and the f-string statement was mofidied to limit the percentage to one decimal place. Finally, in order to determine the winning candidate, vote count, and percentage, a decision statement was used to compare the number of votes each candidate received. An "if" statement was created inside the "for" loop, and a print statement was added to print each candidate's name, vote count, and percentage. The election audit results were saved to a text file and sent on to the election commission. 

##Challenge Summary 
This was a long coding script that required a great deal of attention and focus to execute properly. I ran into various issues with syntax errors and margins, as well as realizing I needed to switch my Python environment in Visual Studio Code. The winner of the election was utimately determined after analyzing the dataset, and the challenge was successfully completed. 
