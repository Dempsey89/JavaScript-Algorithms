# Missing number Algorithm

  This algorithm took in an array of numbers 0=9, except it was 
  missing a random number and the numbers weren't in order. The
  challenge was to return what that missing number was.
  
  I solved this by sorting the numbers with the sort function. Then
  looping through the sorted list with a for loop, and adding an if
  statement that would return the index number if the value of the 
  indexed number did not equal the index number itself.
