# Digit Degree
	Here the objective was to take in a number, 
	and return the amount of times you would have
	to add the digists of that number up in order
	to get to a single digit.

	I solved this by first setting the number to a string
	that was split. Then I returned 0 if that new arrays length
	was 1. 
	Then looped through the array, and on each iteration used the
	reduced method on the parseInt val of each digit, and returned
	that new number as a split string array.
	Then if the new strings length was 1, I returned that iteration
	plus one.