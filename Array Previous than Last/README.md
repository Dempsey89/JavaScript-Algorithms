# Array Previous Less
	This algorithms objective was to take in an array, then return an array that
	stored the value of the number closest and prior to each number in the array
	that was less than it. If no number existed, than you return a negative one 
	instead.

	To solve this I started by setting a variable equal to an empty array. Then I 
	looped through the array from back to front. Within each iteration, I again looped
	through from back to front from that current index. I then used an if statement 
	to determine if the current value was greater than the next up, and if so I would
	'unshift' that value to the initial variable array I set up and break that 
	iteration- if not I would  instead unshift neg one to that var. Then return the
	new array.