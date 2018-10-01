# Are arrays similar?
	This challenges objective was to find out if the value of two arrays 
	could be equal by moving one of the values in one of the arrays over
	by one. 

	Started by returning true if the two arrays were a match to begin with

	Then I created two variables as empty arrays to store any indexes where they
	 weren't a match to compare at. Then looped through the data of each array, 
	any time the current index of each array didn't match, I added those values
	to each of the array variables I created.

	Then I reversed one of the arrays, and compared it to the other array if the 
	value of the other array was exactly two. I did this because if it was two, and the
	value of the reversed array equaled that array, then you could conclude that you
	could infact make the two arrays equal by moving one value over one slot.