THE PERSON, AGENT, EMPLOYEE, HANDLER, AND STAFF CLASSES



Design a class named Person and its two subclasses named Agent and Employee . Make Handler and Staff subclasses of Employee.

A Person has a name, age, phone number, and e-mail address.

An Agent has a status, one of the following Special, 007, Sleeper, or Double.

An Employee has an office, and a salary. 

A Handler has office hours and a rank.

A Staff member has a title.



All instance variables and all instance methods are public in Python.

So no getters and setters are required.



Add an __init__ and __str__ method for each class .  

In addition add a method isOlder in the Person class so you can compare two objects using the age variable.



In your main function, also in a separate file:



Create two objects of each of the five classes.

Place each of the ten objects into a List named MI5Directory.

Loop through the MI5Directory, and print out the class name, followed by each instance variable name in that class, and its value.

Use the isOlder method on each pair of objects of the same class.
