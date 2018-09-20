# Fizzbuzz challenge
    This version of the fizzbuzz challenge was to return fizz if a given paramater was divisible by three, buzz if it
    was divisible by five, and fizzbuzz if it is divisible by three and five. I came up with two separate solutions for
    the challenge
    
## Solution One
    My first solution was to return a ternary statement that returned fizzbuzz on the condition that the number was
    divisble by three and by five, if not it would return fizz if divisible by three, then if not it would return buzz
    if divisible by five, and then return nothing if none of the prior conditions met.
    
## Solution Two
    My first solution felt a little messy, so I came up with a new one. This time I started by defining a variable with open
    quotes, and then creating two if statements. The first would concat fizz to the variable if the number entered was
    divisible by three, and the second would concat buzz if it was divisible by five.
    
### In both solutions the order of the conditions was important. 
    -In the first, it was important the condition that included a number divisble by three and five went first so that the
    function wouldn't stop running and return just fizz or buzz. 
    
    -In the second, it was important that the condition for if the number was divisible by three was entered first, so that
    it wouldn't concat a number divisible by three and five as buzzfizz. 
