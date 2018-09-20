# Length of longest word

  This algorithm returns the length of the longest word in a string. I ended up coming up with  
  two solutions for this problem

## Solution one
  
  First I split a string param at each space, added array value to variable.
  defined a variable to equal zero.

  looped through the new array with for loop, and if the length of the current
  index value was greater than the ans variable created, it's length would
  become the new value of ans. Once the loop was done, ans was returned. 
  
## Solution two

 Again created variabl the stored split value at each space,
 of string param into an array. This time I then created a variable
 object that sorted through that array and took two paramaters, and returned if 
 the length of the first param was greater than the length of the next. Making a new array
 with the words in order by longest length to shortest. Then returned the length of the
 first value of this array.
