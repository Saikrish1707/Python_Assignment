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
			  It’s similar to an "if-else" statement and the only difference is that in "else" we will not check the condition but in "elif" we will check 				the condition.
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
		  
Q26. What is a string? How can we declare string in Python?
	Strings are arrays of bytes representing unicode characters. 
	Declaration : a = '' or a = ""

Q27. How can we access the string using its index?
	By mentioning the index number square brackets[] 
	

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
	string = "Big Data iNeuron"
	print(string[9:])


Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
	string = "Big Data iNeuron"
	print(string[-1:8:-1])

Q30. Resverse the string given in the above question.
	print(string[-1::-1])

Q31. How can you delete entire string at once?
	By using "del" keyword 
	e.g: del string
	

Q32. What is escape sequence?
	Character combinations consisting of a backslash (\) followed by a letter or by a combination of digits are called "escape sequences

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
	str = "iNeuron's Big Data Course"
	print(str)

Q34. What is a list in Python?
	A list is a data structure in python which can have any number of items and they may be of different types (integer, float, string, etc.)

Q35. How can you create a list in Python?
	lst = []

Q36. How can we access the elements in a list?
	we can access the list by using index 

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
	print(lst[4][2])

Q38. Take a list as an input from the user and find the length of the list.
	list1 = []
	list1.append(input())
	list1.append(input())
	list1.append(input())
	list1.append(input())
	list1.append(input())
	print(len(list1))
	
	or 
	
	list2 = []
	n = int(input("Enter value of n : "))
	for i in range (0,n):
		list2.append(input())
	print(len(list2))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
	lst = ["Welcome", "to", "Data", "course"]
	lst.insert(3,"Big")
	print(lst)
	OUTPUT ===>  ['Welcome', 'to', 'Data', 'Big', 'course']
	
	OR 
	
	lst = ["Welcome", "to", "Data", "course"]
	lst.insert(2,"Big")
	print(lst)
	OUTPUT ===>  ['Welcome', 'to', 'Big', 'Data', 'course']

Q40. What is a tuple? How is it different from list?
	Tuples are used to store multiple items in a single variable. A tuple is a collection which is ordered and unchangeable.
	The primary difference between tuples and lists is that tuples are immutable as opposed to lists which are mutable.

Q41. How can you create a tuple in Python?
	tup = ()

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
	No. We can't add elements to a tuple because of their immutable property. 

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
	No. There's no append() or extend() method for tuples, You can't remove elements from a tuple, also because of their immutability.

Q44. Take a tuple as an input and print the count of elements in it.
	tuple1 = (1,2,3,4,5,'Saikrishna')
	print(len(tuple1))

Q45. What are sets in Python?
	A set is an unordered and mutable collection of unique elements. Sets are written with curly brackets ({}), being the elements separated by commas.

Q46. How can you create a set?
	set1 = set()

Q47. Create a set and add "iNeuron" in your set.
	set1 = set()
	set1.add("iNeuron")
	print(set1)

Q48. Try to add multiple values using add() function.
	set1 = set()
	set1.add("iNeuron")
	set1.add("Big")
	set1.add("data")
	set1.add(1)
	set1.add(1)
	set1.add(2)
	print(set1)

Q49. How is update() different from add()?
	We use add() method to add single value to a set. 
	We use update() method to add sequence values to a set. Here Sequences are any iterables including list , tuple , string , dict etc


Q50. What is clear() in sets?
	The clear() method removes all elements in a set.

Q51. What is frozen set?
	Frozenset is similar to set in Python, except that frozensets are immutable, 
	which implies that once generated, elements from the frozenset cannot be added or removed

Q52. How is frozen set different from set?
	Frozen set is just an immutable version of a Python set object. 
	While elements of a set can be modified at any time, elements of the frozen set remain the same after creation

Q53. What is union() in sets? Explain via code.
	The union() method returns a set that contains all items from the original set, and all items from the specified set(s)
	s1 = {1,2,3,1}
	s2 = {2,3,4,5,1}
	print(s1 | s2)
	OUTPUT ===> {1, 2, 3, 4, 5}

Q54. What is intersection() in sets? Explain via code.
	The intersection() method returns a set that contains the similarity between two or more sets.
	s1 = {1,2,3,1}
	s2 = {2,3,4,5,1}
	print(s1 & s2)
	OUTPUT ===> {1, 2, 3}

Q55. What is dictionary in Python?
	Dictionaries are used to store data values in key:value pairs. 
	A dictionary is a collection which is ordered*, changeable and do not allow duplicates

Q56. How is dictionary different from all other data structures.
	A dictionary is a general-purpose data structure for storing a group of objects. 
	A dictionary has a set of keys and each key has a single associated value. 
	A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

Q57. How can we delare a dictionary in Python?
	dict = {}

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
	<class 'dict'>

Q59. How can we add an element in a dictionary?
	We add a new element to the dictionary by using a new key as a subscript and assigning it a value.


Q60. Create a dictionary and access all the values in that dictionary.
	dict1 = dict()
	dict1['Name'] = 'Ramesh'
	dict1['Surname'] = 'Singh'
	dict1['Age'] = '30'
	dict1['City'] = 'London'
	dict1['Nationality'] = 'Indian'
	dict1['Phone No.'] = '123789456'
	for key,values in dict1.items():
		print(key + ' : ' + values)
		
Q61. Create a nested dictionary and access all the element in the inner dictionary.
	dict1 = dict()
	dict1['Name'] = 'Ramesh'
	dict1['Surname'] = 'Singh'
	dict1['Age'] = '30'
	dict1['Work'] = {'Company Name':'Google','Position':'SDE1','YOE':'5 Years'}
	dict1['City'] = 'London'
	dict1['Nationality'] = 'Indian'
	dict1['Phone No.'] = '123789456'
	for key,values in dict1.items():
		if type(values) == dict:
			for i,j in values.items():
				print(i + ' : ' + j)

Q62. What is the use of get() function?
	The get() method returns the value for the specified key if the key is in the dictionary

Q63. What is the use of items() function?
	The items() method returns a view object that displays a list of dictionary's (key, value) tuple pairs.
	e.g [(key1,value1),(key2,value2),..]

Q64. What is the use of pop() function?
	The pop() method returns the item present at the given index. This item is also removed from the list.

Q65. What is the use of popitems() function?
	Python dictionary popitem() method removes the last inserted key-value pair from the dictionary and returns it as a tuple.

Q66. What is the use of keys() function?
	The keys() method returns a view object. The view object contains the keys of the dictionary, as a list.

Q67. What is the use of values() function?
	The values() method returns a view object. The view object contains the values of the dictionary, as a list.

Q68. What are loops in Python?
	A for loop in Python is a control flow statement that is used to repeatedly execute a group of statements as long as the condition is satisfied.

Q69. How many type of loop are there in Python?
	There are two types of loops in Python, for and while. (Nested for loop)

Q70. What is the difference between for and while loops?
	for ==> A for loop is a single-line command that will be executed repeatedly.
	while ==> While loops can be single-lined or contain multiple commands for a single condition.

Q71. What is the use of continue statement?
	The continue keyword is used to end the current iteration in a for loop (or a while loop), and continues to the next iteration.

Q72. What is the use of break statement?
	'Break' in Python is a loop control statement. It is used to control the sequence of the loop

Q73. What is the use of pass statement?
	The pass statement is used as a placeholder for future code. 
	When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed

Q74. What is the use of range() function?
	The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

Q75. How can you loop over a dictionary?
	By using a for loop.
	e.g : for key,values in dict1.items():


### Coding problems
Q76. Write a Python program to find the factorial of a given number.
	def fact(n):
		if n == 0:
			return 1
		else:
			return n*fact(n-1)
	print(fact(5))    

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
	p = float(input('Enter the Principle Amount :'))
	r = float(input('Enter the Rate of Interest :'))
	t = float(input('Enter the Time Period :'))
	print('Simple Interest is : ',(p*r*t)/100)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
	p = float(input('Enter the Principle Amount :'))
	r = float(input('Enter the Rate of Interest :'))
	t = float(input('Enter the Time Period :'))
	print('Compound Interest is : ',p*(1+r/100)**t)
	
Q79. Write a Python program to check if a number is prime or not.
	number = int(input("Enter a number : "))
	if number > 1:
		for i in range(2,number):
			if (number % i) == 0:
				print(number," is not a Prime")
				break
		else:
			print(number," is Prime")

	else:
		print(number," is not a Prime")

Q80. Write a Python program to check Armstrong Number.
	number = int(input("Enter a number : "))
	n = len(str(number))
	sum = 0
	temp = number
	while temp > 0:
		num = temp%10
		sum += num**n
		temp = temp//10
		
	if number == sum:
		print(number," is a Armstrong Number")
	else:
		print(number," is not a Armstrong Number")


Q81. Write a Python program to find the n-th Fibonacci Number.
	number = int(input("Enter a number : "))
	n0, n1 = 0, 1
	count = 0
	if number == 1:
		print(n0)
	else:
		while count < number:
			print(n0)
			n3 = n0 + n1
			n0 = n1
			n1 = n3
			count+=1

Q82. Write a Python program to interchange the first and last element in a list.
	lst3 = [1,2,3,4,5,6,7,8]
	print('Before Interchanging the first and last element in the list: ',lst3)
	lst3[0],lst3[-1] = lst3[-1],lst3[0]
	print('After Interchanging the first and last element in the list: ',lst3)

Q83. Write a Python program to swap two elements in a list.
	lst1 = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
	lst1[4],lst1[5] = lst1[5],lst1[4]
	print(lst1)
	

Q84. Write a Python program to find N largest element from a list.
	lst1 = [1,2,3,67,93,74,64,7,10]
	num = int(input("Enter a number :"))
	lst1.sort(reverse=True)
	print(lst1[:num])


Q85. Write a Python program to find cumulative sum of a list.
	lst1 = [1,2,3,67,93,74,64,7,10]
	lst_cuml = []
	sum = 0
	for i in range(0,len(lst1)):
		sum = sum + lst1[i]
		lst_cuml.append(sum)
	print(lst_cuml)   


Q86. Write a Python program to check if a string is palindrome or not.
	str1 = input("Enter a string :")
	str2 = str1[::-1]
	if str1 == str2:
		print("The entered string is a Palindrome")
	else:
		print("The entered string is not a Palindrome")


Q87. Write a Python program to remove i'th element from a string.
	str1 = input("Enter a string :")
	n = int(input("Enter a number :"))
	lst_str = [i for i in str1]
	del lst_str[n-1]
	str2 = ''
	for i in lst_str:
		str2+=i
	print(str2)
	
	OR 
	
	str1 = input("Enter a string :")
	n = int(input("Enter a number :"))
	print(str1[:n-1] + str1[n:])


Q88. Write a Python program to check if a substring is present in a given string.
	str1 = input("Enter a string :")
	sub_str = input("Enter a string :")
	if sub_str in str1:
		print(True)
	else:
		print(False)


Q89. Write a Python program to find words which are greater than given length k.
	str1 = input("Enter the string : ")
	k = int(input("Enter a value for k : "))
	lst_str = list(str1.split(" "))
	for i in lst_str:
		if len(i)>k:
			print(i)

Q90. Write a Python program to extract unquie dictionary values.
	dict1 = {'A' : [1, 3, 5, 4], 'B' : [4, 6, 8, 10], 'C' : [6, 12, 4 ,8], 'D' : [5, 7, 2]}
	print(list(set([i for ele in dict1.values() for i in ele])))

Q91. Write a Python program to merge two dictionary.
	dict_1 = {1: 'a', 2: 'b'}
	dict_2 = {2: 'c', 4: 'd'}
	dict_2.update(dict_1)
	print(dict_2)

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
	inp_lst = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
	op_dict = {}
	for i in inp_lst:
		op_dict[i[0]] = i[1]
	print(op_dict)


Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
	inp_lst = [9, 5, 6]
	op_lst = [(i,i**3) for i in inp_lst]
	print(op_lst)

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
	test_tuple1 = (7, 2)
	test_tuple2 = (7, 8)
	op_lst = [(i,j) for i in test_tuple1 for j in test_tuple2] +[(i,j) for i in test_tuple2 for j in test_tuple1]
	print(op_lst)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
	lst_tup = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
	lst_tup.sort(key=lambda z:z[1])
	print(lst_tup)


Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
	n = int(input('Enter a number for printing the design : '))
	for i in range(0,n):
		for j in range(i+1):
			print('*',end=' ')
		print("\n")

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
	n = int(input('Enter a number for printing the design : '))
	for i in range(1,n+1):
		print(" "*(n-i) + "*"*i)

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

	n = int(input('Enter a number for printing the design : '))
	for i in range(1,n+1):
		print(" "*(n-i) + "* "*i)

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

	n = int(input('Enter a number for printing the design : '))
	for i in range(1,n+1):
		for j in range(1,i+1):
			print(j,end=' ')
		print("\n")

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```

	n = int(input('Enter a number for printing the design : '))
	for i in range(1,n+1):
		for j in range(1,i+1):
			print(chr(64+i),end=' ')
		print("\n")
	
