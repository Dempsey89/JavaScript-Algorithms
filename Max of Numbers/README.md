# Max sum of 'k' amount of consecutive numbers
	Here the objective was to take in an array and a number, and return back
	the largest possible sum within that array of the specified number of values
	that consecutively appeared in the array.
	
	To solve this I first set a variable equal to zero. I looped through the array, 
	and on each iteration looped to the number amount. On each of these loops, I added
	all numbers to eachother, and if the sum was larger than my initial variable, I 	
	replaced the variable with this sum.