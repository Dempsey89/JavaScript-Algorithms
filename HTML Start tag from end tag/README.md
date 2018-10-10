# HTML Start Tag from End Tag
	Takes in beginning of an HTML tag as a string, and returns the closing. 	Solved by splitting the string on each space, then 
	split the first value of that new array. Then, if the last value of this 	array was not '>', I pushed it a value of '>' to it. Then, spliced
	that array with a value of '/' at the 2nd index, and returned it's joined 	value