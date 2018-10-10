# Is Lucky
	This algorithm takes in a number, and returns whether the sum of the first 	
	half of the digits in the number equals the sum of the second half of the 	
	numbers. 
	Solved by initially setting a variable to an array by changing it to a 		
	string and then splitting it. Then I created another array that divided 	
	the length of that array by 2. Then set 2 variables to 0.
	Then I looped through the array, and if if the current iteration was less 	
	than the halfway mark, I added the parseInt value of that place to the 	first 0 
	variable, if else I added it to the second. 
	Then I returned a boolean whether the 2 variables equaled each other or 	
	not.