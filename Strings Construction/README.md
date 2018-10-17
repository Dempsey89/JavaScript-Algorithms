# String Construction
	Algorithm takes in 2 strings, and returns the
	amount of times you can recreate the first string
	with the second string if you rearrange the letters 
	in any way. 
	Solving this I created 2 functions. The first would take
	a string, split it, iterate through that array created, and
	add each value of the array as a key to a new object variable
	with the value being one, unless it already had that key in which
	case I incremented the value by one.
	Then, I used that function on each string to create new object variables 
	in my second created function. From there I looped through the first, and
	pushed the value of each value from the second divided by the value of the
	first object into an empty array if that value was in the second object. If
	else, I just returned 0. Then I returned the smallest value of the array.