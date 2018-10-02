# Bot Strategy
	Here the goal was to take in an array of arrays. Each array would have 
	two numbers stored, one stating the 'time' it took for someone to pass a test,
	and the second either a 1 if the actually passed, a -1 if they failed, and a 0
	if they didn't attempt. The task was to return the average time it took for 
	each member in the array to pass, that actually passed. 

	To solve I started by setting a time and correct variable each equal to 0.
	Then I looped through the array, adding 1 to the correct variable on the condition
	that it was equal to 1, and the value of the time it took to the time var if the
	associated correct equaled one. Then I returned the value of the time divided
	by the correct variable.