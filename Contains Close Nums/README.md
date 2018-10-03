# Contains Close Numbers
	This algorithm takes in an array, and a number. The objective
	is to see if the array has any duplicate values, and if so, 
	if the absolute value of the difference of those two value's indexes
	is less than the number paramater.

	I solved this by creating two empty arrays as variables. Then did a 
	forEach loop through the array, and pushed any value to one of the arrays
	if it wasn't in that array already using the indexOf method, then pushed 
	that index value and the current index of the iteration into the other array
	if it was in the first array already.

	This gave me the values of the two duplicate value's indexes in order. So I
	 returned if the number was greater than or equal to the value of the first
	array element subtracted from the second.
	