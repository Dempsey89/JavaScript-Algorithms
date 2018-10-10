# Growing Plant
	This algorithm takes in 3 numbers. 1 represents the growth
	rate of a plant per day, next represents how much it shrinks per night, 		
	and the last represents target height. Based on these numbers, returns 	total 
	amount of days until plant reaches goal height. 
	Solved by setting 2 variables equal to 0. Then looped through while
	height was less than desired height, on each iteration I incremented
	day variable by 1, and height variable by growth rate. Then I used an 
	if statement that returned days if it reached desired height, and 		
	decremented by shrink rate if else.

