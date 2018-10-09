# First Not Repeating 
	This algorithm take in a string, and returns the first
	character that doesn't appear more than once, or _ if no 
	such value exists. 

	I solved by first creating an empty object. Then split the string.
	Then I looped through the new array, and used the hasOwnProperty method
	to check if the obj I created had each value. If it did, I then deleted
	that value, if not I added it to the object. 
	Then I returned a ternary that would return _ if the first value
	of the object was undefined, or the value of it if it wasn't.