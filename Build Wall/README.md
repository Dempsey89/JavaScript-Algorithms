# Build wall
	This algorithm takes in an array, and then adds a 'wall' of stars around each
	item in the array.
	I solved it by creating a var for 3 stars for that would go before and after
	the array begins, and a var equal to one star to go before and after each 
	item in the array.then I pushed and unshifted the first var to the array, then
	mapped through the array returning the second var plus the array item plus the 
	second variable again to return the 'wall' affect.