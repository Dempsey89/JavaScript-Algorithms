# Palindrome Rearranging
	Algorithm takes in a string, and returns whether or not
	the letters in it can be rearranged to make a palindrome.
	Solved by splitting letters in array variable, setting a variable
	to empty object, and another to 0. Then looped through
	the letters array, and added the letter as a key and 1 as the value
	to the object if it didn't already have that property, and incrementing
	that prop by 1 if it did. The I looped through that object and added
	1 to the 0 variable each time the value from the object was not 
	divisible by 2. Then Returned whether that count variable was 
	greater than 1 or not.