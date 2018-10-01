# Array Replace
	The objective here was to take in three paramaters, the first to be an array, 
	the next to be a value to see if that value was in the array, and the last would
	be a value to replace that previous paramter with if it was in the array. 
	I ended up with two solutions for this challenge
## First Solution
	My initial solution was to create an empty array equal to a variable. Then loop
	through the array, and use a ternary on each iteration to see if the current 
	index equaled the value to check for, if so I would push the number that was 
	supposed to replace that value to the var, if not I would push the value of that
	index
## Second Solution
	My next solution was to simply map through the array, then use the same ternary
	as my first solution to return the desired array.