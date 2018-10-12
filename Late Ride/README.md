# Late Ride	
	Algorithm takes in a number that represents the 
	amount of minutes that have passed since midnight.
	Going off of the new military time from this number,
	it returns the value of all digits in that time added
	together.
	I solved by creating a variable that took the value
	of the number divided by 60, rounded down, and turning it to 
	a string, and adding it to the value of the remainder of 
	the number divided by 60 turnded to a string, and split this
	string. Then I returned this string with the reduce method
	adding the parseInt value of each digit to each other.