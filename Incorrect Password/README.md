# Incorrect Password
	Takes in a number, and an array, and compares if there are 10 
	consecutive values in the array that do not equal the number. I solved
	by initiating a variable to 0, then used for loop through the arrays 	
	length. On each iteration, I used a ternary for whether the current
	index equaled the number or not. If it did, I reset the variables value 
	to 0, if not I incremented it by one. If the variable ever
	reached 10, I returned true. if it got through the entie array without 	
	making it to 10, I returned false.
