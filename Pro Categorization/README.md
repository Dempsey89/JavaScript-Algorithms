# Pro Categorization
	This algorithm takes in an array of names, and a second array that represents
	professions each person does. The objective is to return a triple nested array,
	with each profession in alphabetic order as one of the inner arrays, and an array
	of each person who does that profession as the other (both as an array together).

	I solved by initially looping through all the profession arrays, and within that
	loop I looped through each profession. I pushed all values to an empty array variable, 
	and if that array didn't already have the current value, I pushed the value to another array
	variable as well. Then I sorted the second array variable to alphabetic order, then looped through
	it. On each iteration, I looped through each profession array, and if the array had that indexed
	profession we were on, I pushed the inputed name at that index to a new array. Then at the end
	of the loop I pushed the profession, and the names array to another empty array that I ended up 
	returning. 