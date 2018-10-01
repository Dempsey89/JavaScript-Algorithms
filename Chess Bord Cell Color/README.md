# Chess Bord Cell Color
	This algorithm takes in two paramaters that act as positions on a chess bord, 
	ans returns whether they are on the same color cell or not.

	To accomplish this I started by creating an object that stored the y axis positions
	as numbers (values given in format of letter and number to represent x and y axis 
	of bord). Then I created two variables to see whether each was even or not (even
	numbers total would be one color and odd total would be the other color) by adding
	the value of the letter from the object to the parseInt value of the number value, 
	then using the modul to see what it's remainder divided by two was. 

	I then returned a boolean whether the two pieces equaled eachother or not.