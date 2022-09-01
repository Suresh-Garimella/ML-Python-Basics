# ML-Python-Basics
Machine learning Assignment -1
Audio Link:-
GitHub Link:-


	
Question 1:-

In this example we used several list methods :

	list.sort()= It sorts the elements in the list in ascending order.
	min(list),max(list) = using them can get minimum and maximum values.
list.append(val)=It is used to add the value (val) to the existing list.
sum()=It adds all the values of the list.
len()=It gives the length of the list.

Question 2:-
	
In this example we used several Dictionary methods :

	Here we tried different ways of creating and values to the dictionary.
type() - This method is used to determine the type of the variable.
len()- this method is used to get the length of the variable.
dict[“key”].append(val)=It is used to add the value to the given dictionary key.
dictionary.keys()= used to get all the dictionary keys.
dictionary.values()=used to get the dictionary values.

Question 3:-

In this example we used several Tuples methods :
	
	Tuples are immutable.
	So we cannot update the tuple.
	Here we tried different ways of creating and initializing the dictionary.
	And also how to modify the tuples.
type() - This method is used to determine the type of the variable.
len()- this method is used to get the length of the tuple.

Question 4:-


Here we tried several set functions and methods :-
	Set will not contain duplicate values.
	
	type() - Used to return the type of a variable.
	len() - It returns the length of the set.
	add() - using this we can add the elements to the set.
	remove() -using this we remove the values from the set.
	update() - using this we can add multiple values to the set.
discard() - It works same as remove but unlike remove it will not raise an error if the value is not found in the set.
union() - To join two sets.
Intersection() - It returns the common values among two sets.
A.issubset(B) - It returns true if every value of A is present in B.
A.isdisjoint(B) - It returns true if both the sets have Zero common elements.
symmetric Difference() - It returns unique elements in a set that are not present in the intersection of the other set.
A.update(B) - it Adds all the values of the B to A.
A.clear() - It removes all the elements from the set.

Question 5:-

Here we defined a function called area_of_circle having radius as a parameter .
It calculates and returns the area of the circle using the formula pi*r*r.
And also we calculated the circumference of a circle.

Question 6:-

Here we use split() method to break the string using space and returns  them in the list. 
set(list) - It removes all the duplicate values from the list
len() - It returns the length of the list.

Question 7:-

Using split(‘\t’) we split() the string based on the tab space and returns them in the list.
And using a for loop and added keys and values to the dictionary.

Question 8:-
	
In this we learned the string formatting using format() function.

Question 9:

Here we read the input from the user using input() function.
By default the input will take the values in string Format.
So we used int() method to convert the data type to integer.
map(fun,value) :- we use map method to apply the function (fun) to all the value.
list():- we use this method to typecaste the value to list.
append():-used to add the values to the list.

Question 10:-

In this we split the  data set into 2 equal halfs.
one part is used for training he model and the other is used for testing.
Here we used Machine Learning KNN (K nearest Neighbour Method)
then train the model with training data with K value as 3
Then we predicted the output for the testing data set
then we form the Confusion Matrix.

Then calculated the Accuracy , sensitivity(True Positive Rate) and Specificty(True Negative Rate) values using the beow formulas.
Accuracy = (Total Positive + Total Negative)/(Positive+ Negative)
TPR = Total Positive / Positive
TNR = Total Negative / Negative
