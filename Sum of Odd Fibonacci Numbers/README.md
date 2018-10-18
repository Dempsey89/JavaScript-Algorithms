# Sum of Odd Fibonaccis
	Algorithm takes in a number, and returns the sum of all
	the odd fibonacci numbers that are present up to that number.

	To solve, I started by creating 4 variables. One was an number
	var set to 1 to start out at the first fibinacci number. Then 
	was an array, with a value of 0 in it so that I could add the
	previous index to the current fibnacci number each time on my 
	loop later. Then an empty array to store all odd value, and finally
	an itetation variable set to 0.
	Then I used a while loop that ran until the fib number was greater than
	the input number. The first thing done was to push the fib number to the
	array that stored all fibanocci numbers, so that it would now have a value
	of 0 (original value set for array) and 1 (original value of fib number set).
	Then I did an if statement that would push the fib number to the empty odd array
	if the number was odd. Then I added the current indext of the fibanacci array to
	the fib number, so it at this point it would be as if it was adding the prior number
	in the sequence to it each time, and then incremented the index by one.
	Finally, I returned the odd numbers sum with the reduce method.