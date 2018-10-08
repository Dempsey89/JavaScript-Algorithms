# Election Winners
	Here the objective was to take in an array of numbers that 
	represented votes that politicians had, and another number that
	represented the amount of votes left to be made. The goal
	was to return the amount of possible winners left. 

	I solved this by first sorting the arry, and setting a variable
	equal to 0. Then I made an if statement returning 1 if the remainine
	votes equaled 0 and the 2nd number in the sorted array didn't equal the
	first. 
	
	Then I looped through the array, and added to the variable I created by one
	if the current index added to the remaining paramater was greater
	than the last index of the array