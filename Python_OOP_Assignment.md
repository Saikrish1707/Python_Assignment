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

Q19. What happens if you don't do something extra to treat an exception?

Q20. What are your options for recovering from an exception in your script?

Q21. Describe two methods for triggering exceptions in your script.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of
whether or not an exception exists.

Q23. What is the purpose of the try statement?

Q24. What are the two most popular try statement variations?

Q25. What is the purpose of the raise statement?

Q26. What does the assert statement do, and what other statement is it like?

Q27. What is the purpose of the with/as argument, and what other statement is it like?

Q28. What are *args, **kwargs?

Q29. How can I pass optional or keyword parameters from one function to another?

Q30. What are Lambda Functions?

Q31. Explain Inheritance in Python with an example?

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Q34.Explain the use of the 'nonlocal' keyword in Python.

Q35. What is the global keyword?
