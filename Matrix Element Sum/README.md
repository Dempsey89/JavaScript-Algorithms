# Matrix Element Sum
	This algorithm takes in a multidimensional array, where
	each row represents a floor and each column represents a
	room of that floor. If a column value is 0, then we are
	assuming that room and any room in it's column below it
	is haunted, and should therefore be returned back with 
	a representation of 'x'. Then, in the end we want to 
	return the total amount of available rooms, each number
	available represents an available room.
	I solved by initiating 2 variables set to empty arrays
	Then I looped through the array inputed, and on each iteration looped thorugh 
	the array currently indexed, and used an if else
	that had an if else within each scenario. The first was if
	the current index was over 0, then if the current index
	of the current array we were iterating thgouh was 0, or the
	value of the previous index from the new array we created was 'x'.
	then we pushed 'x'. If else, we pushed the index value.
	The next was for if the iteration was at 0, in which
	case I only checked for the current index of the current
	array value being 0, if so pushed the 'x'. On each else statement,
	I added that index value to a variablle I initiated to 0, and
	returned that variable in the end.