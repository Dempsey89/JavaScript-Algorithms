# Largest Product
	Here the objective is to take in an array, and return the largest product of any
	two numbers in a row possible in that array. I came up with two solutions here.

## Solution One
	My first solution involved me creating an empty array, and a variable equal
	to the first two numbers in the array multiplied by each other. Than I looped
	through the array and pushed the product of every number times the next value
	to the empty array. The I looped through this new array and replaced the initial
	variable I got from multiplying the first two values with any number that was
	larger from this new array.

## Solution Two
	My second solution was to again store a variable of the first two numbers product,
	but this time I simply looped through the array once. On each iteration I stored
	the product of the current value times the next one in a variable, and replaced
	the initial value with it if it was larger than it.
	