# Instructor Stats Project
* Developed by Emma Lynn (a02391851@usu.edu)
* Supervised by Neal Legler, CIDI Director (neal.legler@usu.edu)
* On request from Nikole Eyre, Senior Lecturer - English Department

## Requirements & Design
Nikole wants to get information from all the classes she's taught in the past 10 years, to fill in a table
like this one:

<img src="./ex-table.png">

Tasks:
* Figure out how to pull the id of every course she has taught since Fall 2013
* Divide these courses by course and delivery method

### Data to return:

Course name
* Total sections: #
* Total students: #
* Traditional sections/students: #/#
* Online sections/students: #/#
* Broadcast sections/students: #/#
* Blended sections/students: #/#

## Progress

### 6.20.23
* The `List courses for a user` call looks very promising
* Nikole's a-number: a00344330
  * Canvas ID: 54650
* Got the data I think I need, now I just need to parse it

### 6.21.23
* Finished formatting data and gave it to Nikole


## Sources / References
* https://canvas.instructure.com/doc/api/courses.html
* https://www.usu.edu/registrar/scheduling/section-codes
* https://www.usu.edu/registrar/scheduling/deliverymethods

