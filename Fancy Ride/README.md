# Fancy Ride
	Here the objective is to take in a number represnting
	the amoutn of time an uber customer will be in a car, 
	and an array specifying the cost of various uber cars
	per per minute. The goal is to return which car the
	customer can get for under $20, based off of 5 different
	options.
	
	I solved by first creating an object with 0-4 keys, each
	with one of the cars as values. 
	Then I made a for loop that started at the cost length, and
	went back one on each iteration. I then returned the current car
	key if the current cost index times the cost was less than or
	equal to 20.

	