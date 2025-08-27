# ASSIGNMENTS
QUESTIONS THAT WERE THERE IN THE PYTHON COURSE 
Problem Statement: Write a Python program that:
q1. Takes two numbers as input from the user.
   Performs the basic mathematical operations on these two numbers:
	 Addition
	 Subtraction
   Multiplication
   Division
   Displays the results of each operation on the screen.

SOLUTION: 
#Addition of 2 numbers
number1= float(input("Enter the number1:"))
number2= float(input("Enter the number2:"))
Addition= number1+number2
print('Addition:', Addition)
Subtraction= number1-number2
print('Subtraction:', Subtraction)
Multiplication= number1*number2
print('Multiplication:', Multiplication)
Division= number1/number2
print('Division:', Division)
   

Q2.  Takes a user's first name and last name as input.
    Concatenates the first name and last name into a full name.
    Prints a personalized greeting message using the full name.
	
SOLUTION:
#Greeting message 
FirstName = str(input("Enter your first name: "))
LastName = str(input("Enter your last name:"))
FullName = FirstName + " " + LastName 
GreetingMessage= "Hello, " + FullName + "! Welcome to the Python's World"
print("GreetingMessage", GreetingMessage)


 
