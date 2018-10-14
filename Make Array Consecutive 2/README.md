# Make Array Consecutive
	Takes in an array of positive numbers, and returns the number of 
	missing numbers in order to make the array an in order array 
	that increments by 1 each time.
	Solved by first sorting the array, then looping through
	from the smallest value in it to the largest, and added
	1 to a variable I initially set to 0 each time the array
	didn't include the value of the current index. Then
	returned that variable