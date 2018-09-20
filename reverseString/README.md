# Algorithm to Reverse Strings

## Solution one
  Created a variable that split a string value
  into an array of characters, then reversed that
  array as the value of a new variable, and returned
  the joined value of that reversed variable.
  
 ## Solution two
  Similar to the prior solution, but with no variables.
  Returned the string paramater after it was split, reversed,
  and then joined back together.
  
 ## Solution three
  Created a variable equal to empty string. Then created a for loop
  that started at the end of the string paramater (by using str.length),
  and went backwards until it looped through the string. Each value of the 
  loop was added to the variable created and once the loop stopped running
  that variable got returned. 
  
  ### Reason for using for loop
   Even though it doesn't take advantage of some of the newer built in JavaScript
   functions and it takes more code to write out, the for loop may have been the 
   best solution. While the other solutions loop through multiple times to split,
   reverse, and then join the string, the for loop only loops once to add the values
   to the variable that ended up being returned. 
