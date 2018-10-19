# Unique Values
	Takes in an array, and returns back the number of unique
	values of each number in the arrays digits products. Solved
	by first creating an empty object to store unique values, then
	another variable to store multiples. Then I looped thorugh the array,
	and on each iteration I turned the number to a string and split it, if
	the length of this new array was 1 of less, I made the multiple value
	equal to the parseInt value of it, if else I made the multiple variabl
	equal to the reduced value of it's parseInt values multiplied. Then
	I checked if the object had that multiple as a property, if not added it
	as one. Then returned that objects length of keys.