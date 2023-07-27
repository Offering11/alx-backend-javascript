ES6 Classes
This project contains tasks for learning to use classes in ECMAScript 2015 (ES6).

Tasks To Complete

 0. You used to attend a place like this at some point
0-classroom.js contains a script that exports a class named ClassRoom with the following requirements:

Prototype: export default class ClassRoom.
It should accept one attribute named maxStudentsSize (Number) and assigned to _maxStudentsSize.
 1. Let's make some classrooms
1-make_classrooms.js contains a script that meets the following requirements:

Import the ClassRoom class from 0-classroom.js.
Export a function named initializeRooms. It should return an array of 3 ClassRoom objects with the sizes 19, 20, and 34 (in this order).
 2. A Course, Getters, and Setters
2-hbtn_course.js contains a script that exports a class named HolbertonCourse with the following requirements:

Constructor arguments:
name (String).
length (Number).
students (array of Strings).
Make sure to verify the type of attributes during object creation.
Each attribute must be stored in an "underscore" attribute version (ex: name is stored in _name).
Implement a getter and setter for each attribute.
 3. Methods, static methods, computed methods names..... MONEY
3-currency.js contains a script that exports a class named Currency with the following requirements:

Constructor arguments:
code (String).
name (String).
Each attribute must be stored in an "underscore" attribute version (ex: name is stored in _name).
Implement a getter and setter for each attribute.
Implement a method named displayFullCurrency that will return the attributes in the format name (code).
 4. Pricing
4-pricing.js contains a script that meets the following requirements:

Import the class Currency from 3-currency.js.
Export a class named Pricing that meets the following requirements:
Constructor arguments:
amount (Number).
currency (Currency).
Each attribute must be stored in an "underscore" attribute version (ex: name is stored in _name).
Implement a getter and setter for each attribute.
Implement a method named displayFullPrice that returns the attributes in the format amount currency_name (currency_code).
Implement a static method named convertPrice. It should accept two arguments: amount (Number), conversionRate (Number). The function should return the amount multiplied by the conversion rate.
 5. A Building
5-building.js contains a script that exports a class named Building with the following requirements:

Constructor arguments:
sqft (Number).
Each attribute must be stored in an "underscore" attribute version (ex: name is stored in _name).
Implement a getter for each attribute.
Consider this class as an abstract class. And make sure that any class that extends from it should implement a method named evacuationWarningMessage.
If a class that extends from it does not have a evacuationWarningMessage method, throw an error with the message Class extending Building must override evacuationWarningMessage.
 6. Inheritance
6-sky_high.js contains a script that meets the following requirements:

Import Building from 4-building.js.
Export a class named SkyHighBuilding that extends from Building and meets the following requirements:
Constructor arguments:
sqft (Number) (must be assigned to the parent class Building).
floors (Number).
Each attribute must be stored in an "underscore" attribute version (ex: name is stored in _name).
Implement a getter for each attribute.
Override the method named evacuationWarningMessage and return the following string Evacuate slowly the NUMBER_OF_FLOORS floors.
