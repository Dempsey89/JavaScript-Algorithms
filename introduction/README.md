# Combine strings algorithm
    This is an algorithm that takes in two string paramaters, and then adds them to a sentence that introduces someone by
    their first and last name. I came up with three different solutions to this algorithm
    
## Solution one
    The first solution I came up with was to return a string with the introductory info in quotes, then add together the
    firstName ans lastName parameters  with a quote with a space between them, and then add a quote for the period to it
    at the end.
    
## Solution two
    This solution was to create two variable, one that concated the firstName with a quote with spaces and with the lastName,
    the other var held the value of the introductory sentence with a space at the end. The the function returned the value
    of these strings concatted together and with a quote for the period at the end.
    
## Solution three
    The third solution was to simply return a sentence using template literals, which use backticks to wrap around the
    sentence and then the format ${param} to add the first and last name where appropriate in the sentence. 
