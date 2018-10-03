# Compose Ranges
	This algorithm took in an array of numbers, and returned
	an array of the ranges that are in sequence, as a string with
	an arrow from the first to the last in that sequence.i.e ([1,2,3,4,6,7,9])
	would return "1->4","6->7","9".

	I ended up using two solutions here. 

## Solution One
	The first solution envolved initiall looping through the array, then 
	pushing each value to one empty array if it wasn't one higher than 
	the last previous index value, and adding the number to another array
	if it wasn't one less than the next index. 
	
	Then I looped through those arrays, and pushed the values of each index
	of the prev two created arrays as an array of two values at each index for 
	each. Then I mapped through this array, and if the two values were equal 
	to each other, I returned just the first one as a string, otherwise I 
	returned the first and second as strings with the arrow in between them.

	This solution worked, but did a lot of looping. The following solution
	was done by Dylan Israel in his Udemy course and I think it works a little
	better.

## Solution two
	This solution initially creates an array with an object as the first item.
	This item has a start and end key, which are both set equal to the first 
	number of the array.Then, it iterates through the array starting at 1 in 
	a for loop. If the value of the 'end' property + 1 matched the current iteration,
	the end property would be replaced with that iteration value. If not, the array
	would push another object to it, with the start and end prop set equal to the 
	current iteration value.

	Then it iterates through this object with another for loop, this time
	iterating through that array of objects created. If the start and end
	were not equal, it set the value equal to each as a string with th arrow
	between using template literals. If else it returned the value of the 
	start tostring.
