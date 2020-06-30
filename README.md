# Date-Class
Design a class called Date. The class should store a date in three integers: month, day and year.
There should be member functions to print the date in the following forms:
12/25/2012
December 25, 2012
25 December 2012

Input Validation: Do not accept values for the day greater than 31 or less than 1. Do not accept values for
the month greater than 12 or less than 1.
Demonstrate the class by writing a main program to implement it

Extend/modify the above Date class to contain the following overloaded operators:
++ Prefix and Postfix increment operators: These operators should increment the object’s day member.
 -- Prefix and Postfix decrement operators: These operators should decrement the object’s day member.
 - Subtraction operator: If one date object is subtracted from another, the operator should give the number
 of days between the two dates. For example, if April 10, 2012 is subtracted from April 18, 2012, the
 result will be 8.
 << cout’s stream insertion operator: This operator should cause the date to be displayed in the form April
 18, 2012
 >> cin’s stream insertion operator: This operator should prompt the user for a date to be stored in a Date
 object.
 The class should detect the following conditions and handle them accordingly:
- When a date is set to the last day of the month and incremented, it should become the first day of the
following month.
- When a date is set to December 31 and incremented, it should become January 1 of the following
year.
- When a day is set to the first day of the month and decremented, it should become the last day of the
previous month.
- When a date is set to January 1 and decremented, it should become December 31 of the previous year.
Demonstrate the class’s capabilities in a simple program. Save the program as
AdvancedDateDemo.cpp.
Input Validation: the overloaded >> operator should not accept invalid dates. For example, the date
13/45/2012 should not be accepted
