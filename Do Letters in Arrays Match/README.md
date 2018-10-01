# Do letters Match
	This algorithm takes in an array of two strings, and returns back whether
	all the letters of the second word are in the first word
	
	I solved this by initiating an empty variable to begin with, and a variable 
	toLowerCase for the first word, and another variable toLowerCase and then split
	for the second word.
	Then I looped through all the letters of the second word from that knew array
	of it's letters created, and made a statement that turnded the initial empty
	var created to true if the first word included the current iteration 
	(includes method) else it turned it's value to false and then I used a break
	to stop the loop if that was the case, as we would then know there was at least
	one letter that didn't match.
	Then returned the value of that variable.