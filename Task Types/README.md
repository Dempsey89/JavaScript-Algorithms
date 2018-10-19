# Task Types
	Takes in an array and a number. Array represents tasks
	and days they were supposed to be done. Number represents current day.
	Objective is to return an array with 3 values, first represnting number
	of tasks do today (which includes tasks from any prior days), second represnting
	tasks due this week, and 3rd representing tasks due next week. 
	Solved by creating variables all set to 0 for each item that will be returned,
	then looped through the array and added 1 to todays variable if the number was less than or
	equal to current value, one to this week if that value minus current day value was 
	less than or equal to 7, or plus one to the last one if else. 