# Century
	The objective of this algorithm was to take in a number paramater that
	represented a year, and return what century that year was in. 

	I solved this by returning the year minus one, divided by one hundred all wrapped
	within the Math.floor method, and then adding one to that number. This would
	account for years that ended exactuly on 1000 increments by bringing the total
	down to 999 before dividing by 100.