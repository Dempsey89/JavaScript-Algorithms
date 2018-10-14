# New Numeral system
	Objective was to take in a letter that represented a new number system,
	with A being 0, B being 1, and so on. Goal was to return an array with every
	combination of letters that would equal the inputted letters value if added together.
	I solved by first creating an object with all the letters as keys and the numbers
	as their values. Then I created an empty array variable. Then I did a for loop
	going to the  value of the inputted array divided by 2, and pushed the value
	of each iterantion and the inputted value minus the iteration value on
	each iteration.