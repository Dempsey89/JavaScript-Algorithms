# Sum of digits present in a string
   This algorithm adds up all of the numbers in a string, regardless of if there are letters/special characters between
   the numbers or not. To do this I first split the string into an array at each space, and then filtered that array
   with a parseInt function to return an array with only the numbers. I then mapped that array with the Number function
   to change it from a string to a number value. Finally, I returned a ternary statement that would return 0 if the
   length of this new string was 0, and a reduced array that added the numbers together if the length was not equal
   to 0.
