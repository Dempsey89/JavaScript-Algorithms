# Super Digits Sequence
	Algorithm takes in a number, and returns the amount
	of times it would take to add the digits in it squared 
	together to come across a number it has come to already. 
	I started by initiating a variable equal to an array with the 
	input number as an item. Then Another variable that took in the 
	input number, set it to a string, mapped through it returning the
	parseInt value to the second power of each digit, and then reduced
	that array to the sum of the items.
	Then I did a while loop, that returned the length of the array I created plus
	1 if that array included the new number var I created (Added one because the
	problem assumed you would still have to multiply the digits that last time). If
	else, I pushed the number to the array, then did the same list of methods on the 
	new variable number again as I did to get it. This loop goes until it finds a matched
	value.