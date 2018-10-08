# Even Digits Only
	This algorithm takes in a number, and returns the
	wheter or not every digit in that number are even.
	 I solved in two ways. 

	For both, I started by setting the number to a string and 
	splitting it into an array. 

## Solution one
	My first solution was to loop through this array and returning
	false if any index divided by two didn't have a remainder of 0.

## Solution two
	My second solution was to simply use the every method for 
	all digits and return a boolean whether each number divided
	by 2 had a remainder of 0 or not.