# Convert Strings
	This challenge was to take in two strings, and return
	whether you could make the first equal the second by 
	removing letters from it. I solved by setting each string
	to an array variable with the split method. then I looped 
	through the second, and used the indexOf method to check
	if the first string contained each letter of the second. 
	If it didn't, I returned false, if it did, then I sliced
	the first string from that index plus one, so it would be
	removed from the array to make sure the values were all in 
	order and there were the correct amount of values of each
	letter. If it made it through the loop without returning false,
	I returned true.
