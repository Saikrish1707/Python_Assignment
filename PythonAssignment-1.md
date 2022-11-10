## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
	Because python is a interpreted language and its interpreter run through the code and translates the code into machine readable byte code.

Q2. Why is Python called a dynamically typed language?
	Because Python interpreter does type checking only as code runs, and the type of a variable is allowed to change over its lifetime.

Q3. List some pros and cons of Python programming language?
	Pros:
	1. Easy to Read, Learn and Write
	2. Improved Productivity
	3. Interpreted Language
	4. Dynamically Typed
	5. Free and Open-Source
	6. Vast Libraries Support
	7. Portability
	
	Cons:
	1. Slow Speed
	2. Not Memory Efficient
	3. Database Access
	4. Runtime Errors

Q4. In what all domains can we use Python?
	Artificial Intelligence, Machine learning, & Deep learning, 

Q5. What are variable and how can we declare them?
	A Python variable is a symbolic name that is a reference or pointer to an object. 
	Declaring a variable : 
	1. Name the variable
	2. Assign a value to the variable

Q6. How can we take an input from the user in Python?
	By using the input function (i.e input())

Q7. What is the default datatype of the value that has been taken as an input using input() function?
	String

Q8. What is type casting?
	converting the datatype from one to other datatype (i.e number 13 can be converted to string 13 by using type() function)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
	Yes,  by using ==> a, b, c = input().split() 

Q10. What are keywords?
	 Keywords are predefined, reserved words used in Python programming that have special meanings to the compiler

Q11. Can we use keywords as a variable? Support your answer with reason.
	 No, Keywords are predefined, reserved words used in programming that have special meanings to the compiler.
	 

Q12. What is indentation? What's the use of indentaion in Python?
	 Indentation refers to the spaces at the beginning of a code line. The use of indentaion is to indicate a block of code.

Q13. How can we throw some output in Python?
	 By using print function (i.e print())

Q14. What are operators in Python?
	 Operators are special symbols in Python that carry out arithmetic or logical computation
	 +,-,*,/,//,%,**


Q15. What is difference between / and // operators?
	 /  ==> Divide left operand by the right one 
	 // ==> Floor division - division that results into whole number adjusted to the left in the number line

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
	 str = 'iNeuron'
	 print(str*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
	 num = int(input("Please enter a number : "))
	 if num % 2 == 0:
		print("The entered number is EVEN")
	 else:
		print("The entered number is ODD")

Q18. What are boolean operator?
	 Boolean operators are those that take Boolean inputs and return Boolean results.
	 NOT, AND, OR

Q19. What will the output of the following?
```
1 or 0 ==> 1

0 and 0 ==> 0

True and False and True  ==> False 

1 or 0 or 0 ==> 1
```

Q20. What are conditional statements in Python?
	 Conditional Statements are used to handle conditions in your program. 
	 These statements guide the program while making decisions based on the conditions defined in the program.

Q21. What is use of 'if', 'elif' and 'else' keywords?
	 IF ==> It checks for a given condition, if the condition is true, then the set of code present inside the "if" block will be executed otherwise not.
	 ELIF ==> "elif" statement is used to check multiple conditions only if the given condition is false. 
			  It’s similar to an "if-else" statement and the only difference is that in "else" we will not check the condition but in "elif" we will check the condition.
	 ELSE ==> "else" block will be directed to perform the action only the condition mentioned in the "if" block is not matched.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
	 age  = int(input("Please enter your age : "))
	if age >= 18:
		print("I can vote")
	else:
		print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
--1st approach
total_sum = 0
for i in numbers:
    if i % 2 == 0:
        total_sum+=i
print(total_sum)

--2nd approach
total_even_sum = 0
print(sum([total_even_sum+i for i in numbers if i % 2 ==0]))



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
	 a, b, c = input("Please enter three numbers : ").split()
	 if a>b and a>c:
		print("The Greatest Number is : ", a)
	 elif b>c:
		print("The Greatest Number is : ", b)
	 else:
		print("The Greatest Number is : ", c)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

--1st approach
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i % 5 == 0:
        print("This Number is divisible by 5 : ", i)
    if i > 150:
        print("Skipped Number is : ",i)
        pass
    if i > 500:
        print("Loop got broked at : ",i)
        break

--2nd approach
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i % 5 == 0:
        print("This Number is divisible by 5 : ",i)
        if i > 150:
            print("Skipped Number is : ",i)
            pass
        if i > 500:
            print("Loop got broked at : ",i)
            break 
