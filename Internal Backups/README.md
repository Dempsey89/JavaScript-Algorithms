# Internal Backups
	Takes in number that represents the last time a file backup was made, and 		
	an array of nested arrays that represent times that files were changed, 	
	and the file ID. Goal is to find which files have been updated since 	
	backup, and return those ID's in numerical order and with no duplicates. 
	I solved by setting an empty array variable, then I looped through the 		
	array of file updates. On each iteration, if the update number was larfer 		
	than backup, and if the empty array I created didn't have the file ID in 	
	it, I pushed that file ID to it. 
	Then I returned that array variable with the sorted method