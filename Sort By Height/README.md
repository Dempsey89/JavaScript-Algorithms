# Sort by Height
	Algorithm takes in an array of numbers representing people 
	in a groups heights, and also trees which are represented
	by -1. The objective is to return the array back in order
	from shortest to tallest, but with the "trees" in the same
	place they were in the original array. I solved by first
	filtering through the ray to get rid of -1s, and then sorting
	this new array. Then I looped through the original array, and
	added the new value at each place index that didn't equal -1
	by replacing it with the index of a variable I initially set to 	
	0, and incremented by one on each iteration of the loop.