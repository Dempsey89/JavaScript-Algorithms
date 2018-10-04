# Crossing Sum
	This challenge was to take in a multidimensional array, an 'a' value number, 
	and a 'b' number value. The array was supposed to represent a box,
	while a was supposed to represent the rows and b the columns. 
	
	The objective was to return the total of all the values in the specified 'a'
	row, plus all the values of each rows 'b' specified column. (skipped 'b'
	because I would be adding all 'b' values in my next step).

	I solved this by setting two variable equal to 0. Then I looped through the 
	array's 'a' index, and added all values to the first variable except the one
	at the 'b' column, using an if statement. 

	Then I looped through the entire array, and added each 'b' column value to 
	the second variable. Then I returned the two variables added together. 