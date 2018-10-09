# Flatten Array
	Here the goal was to take in a multidemensional array, 
	and return only the values of it in another array. 
	I solved this by first creating an array set to an empty
	arrat. Then I used recursion on the array paramater, by
	using a forEach on it that went back through the array
	if the value was an array using Array.isArray() method, or
	pushed the value to the empty array created if else.

