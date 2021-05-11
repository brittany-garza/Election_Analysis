## Election_Analysis

# 1. Overview of Election Audit: 
	With this challenge, I will be providing a breakdown of each county. 
	This will provide insight on which county had the most voter participation.   

# 2. Election-Audit Results:  
	• How many votes were cast in this congressional election?
	
	The total number of votes in the election is 369,711. 
		

	• Provide a breakdown of the number of votes and 
	  the percentage of total votes for each county in the precinct.
	  
	Denver county had the most votes with 306, 055, equaling out to 82.8%. 
	Jefferson county had a total of 38,855 votes which is 10.5% of the total election. 
	24,801 or 6.7% of the votes belong to Arapahoe county.  
		
	The dictornary named counties_dict will hold the county names and vote information. 
	I created a list called counties_list to hold the names of the different counties.
	Then used county_name to extract the different counties from all the rows in the csv file.
	Below is the if statement that is ran while the system is reading all the rows. 
	If the system sees a county that is not on the list, it will automatically be added then tracked. 
	When the system sees multiple rows with the same county name then a running count is kept. 
	
![County_count_if](https://user-images.githubusercontent.com/82127584/117897807-27a01b80-b289-11eb-80bc-0e75e2fbfb3c.PNG)
		
		
	• Which county had the largest number of votes?
		
	Denver county had the largest voter turnout. 

	• Provide a breakdown of the number of votes and 
	  the percentage of the total votes each candidate received.
	  
	Raymon Anthony Doane votes made up only 3.1% or 11,606 of the total election.
	85,213 or 23% of the votes belong to Charles Casper Stockham. 
	Diana DeGette won by having 73.8% or 272,892 of the votes in her favor. 

	Tracking the candidate information is similar to the county name if statment. 
	Information on the candidates and votes is storaged in a dictonary called candidate_votes. 	
	The names of the candidates is added to a list candidate_options while the csv file is read through.
	The code tracks the amount of times a candidates name is mentioned then stored in the dictonary. 
		

	• Which candidate won the election, what was their vote count, 
	  and what was their percentage of the total votes?
	  
	The winner of the election is Diana Degette with a total of 272,892 votes and a winning percentage 73.8%


# 3. Election-Audit Summary: 

	Since counties are divided by precincts, the script can be modified to 
	show voter turnout within each precinct. This will give better insight on which areas 
	need more voting resources.  
	
	The script can be modified to show which party had a higher voter turnout. 
	Combine the script with the previous example of voter turnout by precincts, 
	this will show which areas had more voters. This will show the election committees
	which areas the party candidate will need to campain in. 
