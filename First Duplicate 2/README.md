# First Duplicate
	I came across this algorithm again and came up with 
	a better solution. The goal here is to take in an array, and
	return the first char that is a duplicate, or -1 if there are none.
	I solved this time by creating a variable set to an empty object. 
	Then I looped through the array, and returned the current value if
	the object I created had it as a property with hasOwnProperty method, 
	and if not I added it to the object. 

	If it made it through the loop without finding a duplicate, I returned
	-1.