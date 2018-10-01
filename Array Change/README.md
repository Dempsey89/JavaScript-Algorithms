# Array changes
	This algorithms objective was to take in an array, and return the amount of 
	'changes' needed to convert the array so that it was in numerical order going 
	up incrementally. I had two solutions for this challenge.
## Solution One
	My initial solution was to create a variable equal to zero, then loop through
	the array, and within each iteration loop through the array again while the current 
	index was greater than or equal to the next index, and on each of these iterations
	add one to the next index and one to the initial variable set up. Then I would 
	return the value of the var at the end.
## Solution Two
	The solution I saw from the udemy course I am doing I liked better than mine. 
	It was set up similar by initializing the var to zero and looping through the
	array. But then, an if statement is created if the current index is greater than
	or equal to the next index, that creates a var equal to the difference of the 	current index minus the next index, and adds that value to the initial set up var
	each time. This way you don't have to loop through the array nearly as much.
