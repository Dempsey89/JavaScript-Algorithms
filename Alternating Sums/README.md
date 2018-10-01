# Alternating Sums
	The goal of this algorithm was to take in an array, and return the
	total sums of both the odd integers of the array and even integers of the array.
	I ended up with two different solutions for this.
## First Solution
	My first solution created a variable set to an empty array for odd and another
	for even. Then I looped through all the values, pushed the val of the index
	to the odds, then added another to my index(I) variable and pushed that new
	index value to the evens as long as it wasn't greater than the array length.
	Then I created a function that used the reduce method to add all numbers in 
	an array, and then returned both the odd and the even array with the reduce
	function called on each
## Second Solution
	Next solution was much quicker and cleaner, one I saw from a udemy algorithm
	course I am taking. Here I instead created the odd and even variables as equal
	to zero. Then did a forEach loop that would add the value to odd if the number
	was odd, and even if it was even. Then just returned the two variables. 