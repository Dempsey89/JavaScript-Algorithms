# Find Closest pair
	Here the objective was to take in an array and
	a number, and return the distance between the closest
	2 numbers whose sum would equal the number, unless there
	were none in which case you would return -1.

	I solved by setting a variable to an empty array. Then looping through
	the array param, and within that loop, looping through it starting one head.
	 Any time where the sum of array value at the current index of the first
	loop and the array value of the index of the second loop equaled
	the number, I would push the index of the second loop minus the index of the
	first loop into the variable I created. 
	Then I sorted the array, and returned either -1 if the arrays length was 0, or 
	the value of the first index of the variable if else. 