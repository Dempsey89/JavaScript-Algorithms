# Seek and Destroy
	Takes in 2 arrays of numbers, and returns an array of any
	number that is in the first and not the second. I solved by
	setting a variable to an empty array, then looping through
	the first array input, and pushing the index of it to the variable
	if it was not included in the second using the includes method.
	Solved second way by setting values of second array to object values
	by looping through it and assigning each value to a value of the object, 
	then looped through the first array and pushed each number that wasn't
	a property of that object using the hasOwnProperty method