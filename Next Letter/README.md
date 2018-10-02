# Next letter in alphabet
	This challenge was to take in a string, and return back a string
	with each letter one value higher.

	To solve this I first declared an empty array variable. Then I looped 
	through all the letters in the string, and pushed the charCode of each
	to the array I created. Then I mapped though that array, and added one
	to each value unless the value was 122 (z), in which case I chanfed the value
	to 97 (a) using a ternary.

	Then I mapped through that array, returning the String from charCode methods
	of each value.