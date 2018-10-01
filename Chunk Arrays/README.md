# Chunk Array
	This algorithm takes in an array and a number as paramaters, 
	then returns an array of arrays the size of the number that was
	given.
	
	First I created a var that out of the array using the slice method starting
	at 0 and going to the number given. Then another array that stored used slice
	again but started at the number and went to the end of the array. 
	The first array was used as the only item in a new array created as a variable.
	Then I looped through the second array I created. On each iteration I pushed
	a sliced portion of that array into the third array created, and changed the
	value of the second array to it sliced at the number paramater to the end of 
	it's length.
	Then, if the remaining length of that array I was iterating through was less
	than the number paramater and greater than 0, it would push the rest of the 
	array into that third array I created. Then I returned that third array after 
	the loop.