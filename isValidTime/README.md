# Is value a valid time

  This algorithm checks if a given string is a valid time amount (army time 00:00-24:00).
  To solve it I first created a variable that stored only the number values of the string
  paramater entered by splitting it with a regular expression. Then I targeted the third
  value in the array to see if it was greater than five, if so the function would return
  false since the minutes can't go over 59. If the third value was five or under, I 
  returned a ternary statement checking if the parseInt value of the original variable
  created. This statement returned true if the value was equal to or under 2400 and 
  equal to or over 0, and false otherwise.
