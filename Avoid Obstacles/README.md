# Avoid Obstacles
	This algorithm took in an array of numbers that served as points where
	an obstacle would be. The objective was to find the smallest number that it
	would take in order to be able to 'leap' to avoid landing on any of them.

	I started by sorting the array so they were all in numerical order. Then I 
	stored the highest value in a variable.

	Next I looped through the array starting at 1, and returned the index number 
	itself once it got to a point that it wasn't divisible by any of the values
	in the array by using the every method. Had to start at 1 to avoid an infinite 
	loop. If any number is not divisible by each of the values, it will never land 
	on any of them if incrementing by that amount at a time.