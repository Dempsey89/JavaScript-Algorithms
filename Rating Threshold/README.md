# Rating Threshold
	Takes in an array with nested arrays of values within,
	each value representing a person an ratings they recieved. 
	Objective is to return back any person whose average rating
	is less than 3.5
	To solve, I looped through the array, and used an if statement, 
	if the current index values added together with the reduce method, 
	and divided by the total length of the values was less than 3.5, 
	I pushed the index to an array variable that I returned at the end.