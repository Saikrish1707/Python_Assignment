Q1. What is the purpose of Python's OOP?

Ans : An object-oriented paradigm is to design the program using classes and objects. The object is related to real-word entities such as book, house, pencil, etc. The       oops concept focuses on writing the reusable code. It is a widespread technique to solve the problem by creating objects.

Q2. Where does an inheritance search look for an attribute?

Ans : An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses,           progressing from left to right (by default)

Q3. How do you distinguish between a class object and an instance object?

Ans : Object is an instance of a class. Object is a real world entity such as pen, laptop, mobile, bed, keyboard, mouse, chair etc. 
      Class is a blueprint or template from which objects are created. Class is a group of similar objects

Q4. What makes the first argument in a class’s method function special?

Ans : The first argument of every class method, including init, is always a reference to the current instance of the class.

Q5. What is the purpose of the init method?

Ans : The __init__ method lets the class initialize the object's attributes and serves no other purpose. It is only used within classes.

Q6. What is the process for creating a class instance?

Ans : The new operator requires a single, postfix argument: a call to a constructor. The name of the constructor provides the name of the class to instantiate. The new operator returns a reference to the object it created.

Q7. What is the process for creating a class?

Ans : To create a class, use the keyword class:
      E.g. Class example :
                x = 10

Q8. How would you define the superclasses of a class?

Ans : class Class2(Class1) → It means that the class class2 is inherited from the class class1. In simple words, class2 is a subclass of class1

Q9. What is the relationship between classes and modules?

Ans : Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables).

Q10. How do you make instances and classes?

Ans : To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q11. Where and how should be class attributes created?

Ans : Class attributes are the variables defined directly in the class that are shared by all objects of the class.

Q12. Where and how are instance attributes created?

Ans : Instance attributes are attributes or properties attached to an instance of a class. Instance attributes are defined in the constructor. Defined directly inside a class.

Q13. What does the term "self" in a Python class mean?

Ans : The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

Q14. How does a Python class handle operator overloading?

Ans : In Python, overloading is achieved by overriding the method which is specifically for that operator, in the user-defined class. For example, __add__(self, x) is a method reserved for overloading + operator, and __eq__(self, x) is for overloading == .

Q15. When do you consider allowing operator overloading of your classes?

Ans : Consider that we have two objects which are a physical representation of a class (user-defined data type) and we have to add two objects with binary '+' operator it throws an error, because compiler don't know how to add two objects. So we define a method for an operator and that process is called operator overloading.

Q16. What is the most popular form of operator overloading?

Ans : A very popular and convenient example is the Addition (+) operator. Just think how the '+' operator operates on two numbers and the same operator operates on two strings. It performs “Addition” on numbers whereas it performs “Concatenation” on strings.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

Ans : Inheritance and Polymorphism

Q18. Describe three applications for exception processing.

Ans : 
Raised when the specified key is not found in the dictionary. 
Raised when an identifier is not found in the local or global namespace. 
Raised when trying to access a local variable in a function or method but no value has been assigned to it

Q19. What happens if you don't do something extra to treat an exception?

Ans : When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed.

Q20. What are your options for recovering from an exception in your script?

Ans : You can also provide a generic except clause, which handles any exception. After the except clause(s), you can include an else-clause. The code in the else-block executes if the code in the try: block does not raise an exception. The else-block is a good place for code that does not need the try: block's protection.

Q21. Describe two methods for triggering exceptions in your script.

Ans : There are two methods to handle Python exceptions: 
      Try – This method catches the exceptions raised by the program. 
      Raise – Triggers an exception manually using custom exceptions.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of whether or not an exception exists.

Ans : Finally block always executes irrespective of an exception being thrown or not. The final keyword allows you to create a block of code that follows a try-catch         block.

Q23. What is the purpose of the try statement?

Ans : The try statement allows you to define a block of code to be tested for errors while it is being executed

Q24. What are the two most popular try statement variations?

Ans : 
      Try/Except/Else
      When attaching an else statement to the end of a try/except, this code will be executed after the try has been completed, but only if no exceptions occur.
      Try/Except/Finally
      When attaching a finally statement to the end of a try/except, this code will be executed after the try has been completed, regardless of exceptions.

Q25. What is the purpose of the raise statement?

Ans : The RAISE statement stops normal execution of a PL/SQL block or subprogram and transfers control to an exception handler. RAISE statements can raise predefined exceptions, such as ZERO_DIVIDE or NO_DATA_FOUND , or user-defined exceptions whose names you decide.

Q26. What does the assert statement do, and what other statement is it like?

Ans : The assert keyword is used when debugging code. The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError.

Q27. What is the purpose of the with/as argument, and what other statement is it like?

Ans : The with statement is a replacement for commonly used try/finally error-handling statements. A common example of using the with statement is opening a file.

Q28. What are *args, **kwargs?

Ans : args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python whereas kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

Q29. How can I pass optional or keyword parameters from one function to another?

Ans : To pass optional or keyword parameters from one function to another, collect the arguments using the * and ** specifiers in the function’s parameter list

Q30. What are Lambda Functions?

Ans : A lambda function is a small anonymous function. A lambda function can take any number of arguments, but can only have one expression

Q31. Explain Inheritance in Python with an example?

Ans : Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes. Base class remains to be the source from which a subclass inherits. For example, you have a Base class of “Animal,” and a “Lion” is a Derived class. The inheritance will be Lion is an Animal.

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?

Ans : 
class A:
    def test(self):
        print("test of A called")
class B:
    def test(self):
        print("test of B called") 
class C(A,B):
    def test(self):
        print("test of C called")
        super().test()     
obj=C()
obj.test()

Output:
abc@f07c99702756:~/workspace$ /bin/python /config/workspace/Assignment_2.py
test of C called
test of A called

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Ans : Using isinstance() function, we can test whether an object/variable is an instance of the specified type or class such as int or list. In the case of inheritance, we can checks if the specified class is the parent class of an object

Q34.Explain the use of the 'nonlocal' keyword in Python.

Ans : The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local.

Q35. What is the global keyword?

Ans : The global keyword is used to create global variables from a no-global scope, e.g. inside a function.
