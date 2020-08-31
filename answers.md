## Tech interview_training

### Question 1 - Variables
*Create a variable and set it equal to 'variable'. What kind of datatype is this?*

variable = 'variable' #this is a String


*Write some few examples of other datatypes in your answers file.*

number = 2  #This is a integer variable
number = 2.5 #this is a float variable

Boolean - an object class

### Question 2 - Hashes and Arrays
*open IRB. we're going to make some cars*

*Create two hashes, one for each car, with the following attributes: wheels, max_speed, color*

carOne = {wheels: "Michelin", max_speed: "200 km/h", color:"red
"}

carTwo = {wheels: "GoodYear", max_speed: "100 km/h", color:"yel
low"}

*Create an array that contains both cars.*

bothCars = [carOne, carTwo]

*How do we use the array to access the second car?*

bothCars[1] which will return: 

carTwo = {wheels: "GoodYear", max_speed: "100 km/h", color:"yel
low"}

 *How do we find the second car's color?*
bothCars[1][:color] which will return:

"yellow"