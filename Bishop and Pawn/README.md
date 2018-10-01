# Bishop and Pawn
	This algorithm takes in two paramaters, one representing a bishops place on
	a chessbord, and one representing a pawns. The objective is to return whether
	the bishop can take the pawn from the current position of each.

	To stard, I created an object that stored all the alphabtic values of the positions
	as number values (each piece has an alphabetic and numeric value for each axis 
	representing where it is on the bord). Then I set the pieces x and y values by
	storing them as variables, the x from that key and the y by using parseInt on the 
	nunmber value. From here I had two solutions
	
## Solution One
	My initial solution involved an if then with three possibilities.
 
	one if the two x values were equal to return a boolean if the y values were as well

	Next I saw if pawns x was greater than bishops x, and if so I would calclulate by
	how much and return a boolean if the bishops y + that difference equaled the pawns
	y.

	Then I did the same except switched the pawn and bishop

## Solution Two
	I saw from the udemy course that this could more easily be solved with one ternary
	which returns true if the bishops x plus bishops y equals pawns x plus pawns y, Or
	if the bishops y plus pawns x equaled the bishops x plus the pawns y.

	I loved seeing how the math worked out for this solution. If the sum of one pieces
	x plus the other pieces y equals the sum of the others x plus the initials y, then
	they must be on the same diagonal plane. 