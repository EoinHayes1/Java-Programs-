Question 1: 
Implement a class named Account that contains:
- A data field named id for an account (default 0).
- A data field named balance for an account (default 0).
- A Date data field named dateCreated that stores the date when an account was created.
- A data field named annualInterestRate that stores the current interest rate (default 0).
Assume all accounts have the same interest rate.
- A no-arg constructor that creates a default account and sets the date of creation.
- A constructor that creates an account with the specified id and balance and sets the date of
creation.
- Getter (accessor) and setter (mutator) methods for id, balance, and annualInterestRate.
- A getter (accessor) method for dateCreated.
- A method named getMonthlyInterest() that returns the monthly interest amount (which
is given by: balance*annualInterestRate/ 12).
- A method named withdraw that withdraws a specified amount from an account.
- A method named deposit that deposits a specified amount to an account.
- A toString() method that returns a string representation of an account (id, balance, and
datecreated)

Question 2: 
Implement a class named RegularPolygon that contains:
- A data field named n that defines the number of sides in the polygon (default value 3).
- A data field named length that stores the length of each side (default value 1).
- A no-arg constructor that creates a regular polygon with default values
- A constructor that creates a regular polygon with the specified number of sides and length of
side.
- Getter (accessor) and setter (mutator) methods for all data fields.
- A method named getPerimeter() that returns the perimeter of a polygon
- A method named getArea()that returns the area of a polygon. 
- A toString() method that returns a string representation of a polygon (i.e. returns the values
of the data fields as a string).

In your setter methods, validate the argument by checking that the user is not providing a negative
number for the number of sides or the length of a side. If they are, print a message and leave the
data field unchanged. Write a test program that creates an array of four RegularPolygon objects
as follows:
