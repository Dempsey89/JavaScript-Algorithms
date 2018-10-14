# Pages Number
	Algorithm takes in 2 numbers. One represents the current
	page number a printer is at to print, and the next represents 
	the amount of digits the printer has ink left to print. The objective
	is to return the number of the last page it can print. I solved
	by setting a variable to 0, then using a while loop for while that number
	was less than the ink count, and on each iteration I added the number
	of digits for each page to that variable (by finding the value of it's length
	in string form), then if that variable plus the next pages length was greater
	than the ink amount, I returned the current page number, if not I added 1 to the page.