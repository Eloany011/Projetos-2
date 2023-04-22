Preface
Requirements
You need to use Python 3 for this assignment. Python 2 is not suitable.

Required Preparation
In order to complete this assignment, you'll probably need to have completed the second module. However, you can get a good start understanding the assignment even having completed just the first module.

Problem Domain
A problem domain is an area of expertise that needs to be understood in order to solve a problem. When programmers are hired, they usually need to learn about their customer's problem domain. For example, if a programmer is hired by a non-profit organization to help with their financial database, that programmer might have to learn how taxes apply to non-profit organizations.

Every assignment in this course will have a problem domain that you will need to learn about.

A1 Problem Domain: Coordinated Universal Time
The problem domain for this assignment involves time zones, and in particular Coordinated Universal Time (UTC), which is "the primary time standard by which the world regulates clocks and time" [Wikipedia]. As you know, there are many different time zones in the world. Wikipedia has a map of the time zones.

As of this writing, there are 40 time zones. One of them, UTC+00:00, is considered to be in the "middle" of the other time zones. All time zones have names, such as UTC+02:00, that indicate the number of hours and minutes they are away from UTC+00:00. For example, the Philippines are in time zone UTC+08:00 because clocks there are set 8 hours later than in time zone UTC+00:00. If it's noon in time zone UTC+00:00, it's 20:00 in time zone UTC+08:00.

Representing hours, minutes, and seconds using a float
In this assignment, we are sometimes going to represent hours and minutes and seconds together as a 
float
float. 1 hour will be represented as 
1.0
1.0, 1 hour and 30 minutes as 
1.5
1.5, and so on.

Preconditions
Some of the functions you will write assume that parameter values are in a certain range. The technical term for these restrictions is precondition: in order for the function to work, the precondition must be met. A precondition is a warning to whoever calls the function that the function was designed to work only under those conditions. When you see a precondition, that means we are guaranteeing that we will only call that function with values that meet the precondition. You can assume that the parameter values meet the preconditions, you do not need to check them. The preconditions are there to make your lives easier!
