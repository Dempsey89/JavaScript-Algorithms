# Index of Number added to Array
	This challenge takes in an array and a number as paramaters, 
	adds the number to the array, sorts it, and returns the position
	that number is in for that array.

	I solved this by initially pushing the number into the array, then
	sorting it from least to greatest. Then I looped through the arrat
	and used an if statement to check if the current indexes value eqauled
	the value of the number. If so, the value of a variable I created outside
	of the loop would be set equal to that index number, I would break out of the 
	loop and return that variable.