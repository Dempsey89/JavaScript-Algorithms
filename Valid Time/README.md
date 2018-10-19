# Valid Time
	Takes in a time as a string, and returns whether it is a valid
	time or not. I solved by creating a variable equal to the string split at the 
	colon, then an hour value that was the parseInt value of the first index, and the minutes
	variable which was the parseInt value of the second index. 
	Then returned a boolean for if minutes was greater than or equal to 0, and less than 24, 
	and if minutes is greater than or equal to 0 and less than 60.