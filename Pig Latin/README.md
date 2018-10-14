# Pig Latin
	This algorithm takes in a string, and returns it
	back as 'piglatin'. The rules are, if the first letter
	of the string is a vowel, it returns the string with 'way'
	attached at the end. If not, then it returns the string startgin
	from the first string, plus the beginning part of the string added at the
	end that was cut off, plus 'ay'.
	I solved by initiating an object with all the vowels as keys. Then
	I used an if statement to check if the first letter of the inputted 
	string was a vowel using hasOwnProperty from that object, if so returned
	the string + 'way'. Then I did a for loop, that would return the string sliced
	at the current index, plus the string sliced up to that index, plus 'ay' if
	the current index was a vowel, again using hasOwnProperty from the object to check.