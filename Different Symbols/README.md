# Different Symbols
	Here the goal was to take in a string, and
	return the amount of unique character in it.
	I ended up with 2 solutions

## Solution one
	My first solution was to create a variable set to 0, and
	another set to an empty array. Then I looped through the
	string after splitting it, and used the indexOf method
	to check if the empty array I created had each value or not,
	if it didn't I pushed it to the array and added 1 to the var
	initially set to 0. Then I returned the count var.
## Solution Two
	My next solution was to create an empty object variable using the
	Set method. Then I did a forEach loop through the split string array
	and added each index to it (which only takes unique values with the
	Set method). Then I returned that objects size.