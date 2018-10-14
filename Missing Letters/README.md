# Missing Letters
	Takes in a string of letters, and if there is a point where
	the string is not in alphabetic order, it returns the missing letter.
	if not, it just returns undefined
	Solved by looping through each letter, and if the char code of the current
	index plus one didn't equal the next indexes charcode value, I returned
	the charcode value of the current indeex plus one, to a string using the String
	.fromCharCode method.