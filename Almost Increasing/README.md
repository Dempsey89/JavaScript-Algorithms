# Almost Increasing
	This algorithms objective was to find out if an array was in numerical
	order that would allow for one 'mistake' or one instance where a value
	was not in order. My solution was to creat a variable set equal to zero, 
	then loop through the array and add one to the variable on any instance
	where the next value in the array was greater thant the current value.
	I also broke the loop and returned false in any situation where the value of
	the current item was less than the value two back and the value of one ahead
	was less than the value of one behind. Because in these circumstances you
	know that there is more than one instance the goal is false without having to 
	loop through the data again.