##PYTHON MEGA PROJECT


Q1. Why do we call Python as a general purpose and high-level programming language?
Ans. We call python a general purpose languge because, it can be used for many applications such as web development, automation, data science etc. We call python a high-level language because, it is more friendly for users and is independent of the computer's hardware architecture.



Q2. Why is Python called a dynamically typed language?
Ans. Python is called a dynamically typed language because in python we don't need to declare a variable. It can simply run the assigned statement as we run the code. Thus we don't need any kind of declaration of data type of the variable. That's why it is called as a dynamically typed language.



Q3. List some pros and cons of Python programming language?
Ans. PROS:--> 
a. It is easy to understand and learn.
b. It is a high level language.
c. It can be used for many domains like data, web, gaming etc.
d. We can complete a task in lesser lines of code.
e. It is free and open-source.
f. It houses lots of libraries.

CONS:-->
a. It has speed limitations.
b. It is not good for game development and high end projects which require high speed operations.
c. It is not good for mobile development.
d. It is still evolving.



Q4. In what all domains can we use Python?
Ans. The following domains can use python:-->
i. Web development
ii. Data science
iii. 3-d modelling
iv. Game development
v. Database accessing 
vi. Robotics and virtual reality



Q5. What are variable and how can we declare them?
Ans. Variable is just like a digital container which holds some kind/type of value. It is a symbolic name given to a reference or pointer of an object. There are different ways of declaring a variable in different programming languages. In python, we can simply assign any value to a variable by simply a name on the left side and the assigned value to its right seperated by a '=' sign.       For ex.: a=50 , in this a is the variable and 50 is its assigned value. We don't need to specify the data type of the variable in the python language coz it is  a dynamically typed language which can identify the data type of a variable all by itself while compiling the code.



Q6. How can we take an input from the user in Python?
Ans. In python, the input() function is used to get input from the user. This function takes input and converts it into a string which can be stored in a variable. The syntax of input function is:  input("enter the input here").



Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans. The default datatype of the value that has been taken as an input using input() function is 'string'.



Q8. What is type casting?
Ans. Type casting is a process of converting one data type to the other. There are two types of type casting: 1. Implicit 2. Explicit
1. Implicit: It doesn't involve the user and converts it automatically.
2. Explicit: It requires user's involvement.



Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans. NO,we can't take more than one input from the user using single input() function because in python the input() function can only take atmost one argument. 



Q10. What are keywords?
Ans. Keywords are special words with special meanings and purpose and can't be used for anything but for those specific purposes. These can't be used as an identifier, function or variable name. All these keywords are used in lower case except True and False.



Q11. Can we use keywords as a variable? Support your answer with reason.
Ans. No, we can't use keywords as a variable because these are predefined and reserved words in the programming language.



Q12. What is indentation? What's the use of indentaion in Python?
Ans. Indentation are the spaces at the beginning of a code line. In python these are used to indicate a block of code which is regarded as the grouping of statement for a specific purpose. Thus, indentations are white spaces which help us indentify the different blocks of code which have a specific purpose.



Q13. How can we throw some output in Python?
Ans. We can use print function to get an output in python.
The synatax is: print(value)



Q14. What are operators in Python?
Ans. Operators are use to perform operations on the variables and values. There are 7 types of operators in python:-
1. Arithmatic operator: used with numerical values to perform mathematical operations.(+,-,* etc)
2. Assignment operator: used to assign values to variables.(=,+=,>>=,<<= etc)
3. Comparison opertor: used to compare two values.(==,!=,<,> etc)
4. Logical operator: used to combine conditional statements.(and,or,not)
5. Identity operator: used to compare object according to their memory allocation and sameness.(is,is not)
6. Membership operator: used to know the presence of one item/sequence in an object.(in,not in)
7. Bitwise operator: used to compare two binary numbers.(&,^,~,<<,>>,|)



Q15. What is difference between / and // operators?
Ans. Both / and // operators are used used for division. Both of them will give user the quotient in return. The only differnce is that, the / operator will give the quotient in float while the // will round the results to the nearest whole number. 



Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans. print("iNeuron"*4)



Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans.
a=int(input("Enter a no. to test even and odd: "))
if(a%2 == 0):
    print("The no. is even.")
else:
    print("The no. is odd.")



Q18. What are boolean operator?
Ans. Boolean  operator are those which help us get a True or False value.
These include and, or and not. These are most commonly used in arithmetic computations and logical comparisons. While and & or need 2 operands, not needs only one.



Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans. Couldn't unterstand the statement. Please let me know the answer to this question!



Q20. What are conditional statements in Python?
Ans. As the name suggests conditional statements refers to the statements use to run a code with certain conditions. It allows conditional execution of a statement.
There are 3 conditional statements: if statement, if-else statement, if-elif-else statement



Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans. These keywords are used to invoke conditional statement in a normal statement. 



Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans. 
age=int(input("Enter your age: "))
if(age>=18):
    print("I can vote")
else:
    print("I can't vote")



Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans. 
numbers = [12, 75, 150, 180, 145, 525, 50]
result=0
for i in numbers:
    if not i%2:
        result +=i
print(result)



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans.
a=int(input("Enter the first no.: "))
b=int(input("Enter the second no.: "))
c=int(input("Enter the third no.: "))
if a>b and a>c:
    print("The greatest no. is",a)
elif b>a and b>c:
    print("The greatest no. is",b)
else:
    print("The greatest no. is",c)



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans. 
numbers = [12, 75, 150, 180, 145, 525, 50]
for number in numbers:

   if number % 5 == 0:

       if number >= 150:

           if number > 500:

               quit()

       else:

           print(number)




Q26. What is a string? How can we declare string in Python?
Ans. A string is a sequence of characters, enclosed in quotation marks. In Python, strings can be declared by enclosing a sequence of characters in single or double quotes.
For example:   Name='jitesh'    or     Name="jitesh"




Q27. How can we access the string using its index?
Ans. In Python, strings are ordered sequences of characters, which means they can be indexed, or accessed by their position in the sequence. The indexing of a string starts from 0, which means the first character of the string is at index 0, the second character is at index 1, and so on.
You can access a specific character in a string by using "square brackets []" and the index of the desired character. For example, if you have a string variable named "string1" with the value "Hello, World!", you can access the second character of the string (the letter "e") like this:
string1 = "Hello, World!"
print(string1[1])  
# Output: e
You can also access a range of characters by specifying the start and end index separated by a "colon :". For example, to access the first three characters of the string:
string1 = "Hello, World!"
print(string1[0:3])  
# Output: Hel




Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"
Ans. 
    string = "Big Data iNeuron"
    desired_output = string[10:]
    print(desired_output)

Here, string[10:] is used to slice the string starting from the 10th index till the end of the string. This would return the substring "iNeuron".



 
Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"
Ans.  
    string = "Big Data iNeuron"
    desired_output = string[10:].lower()[::-1]
    print(desired_output)

Here, string[10:] is used to slice the string starting from the 10th index till the end of the string. string[10:].lower() will convert the string to lowercase. string[10:].lower()[::-1] will reverse the string using slicing by specifying -1 as the step value.




Q30. Resverse the string given in the above question.
Ans.
To reverse a string in Python, you can use slicing with a negative step value, like this:

    string = "Big Data iNeuron"
    reversed_string = string[::-1]
    print(reversed_string)
# Output: norueNi atad giB



Q31. How can you delete entire string at once?
Ans.You can delete an entire string by simply using the 'del' keyword followed by the string variable name.
For example:

    string = "Big Data iNeuron"
    del string
    print(string)

This will delete the entire string, and if you try to print the string after deletion, you will get an error message indicating that the variable is not defined.




Q32. What is escape sequence?
Ans. In Python, escape sequences are used to represent certain special characters within strings, such as newlines, tabs, and quotes. These special characters are not normally printable, so they need to be represented using escape sequences.

Escape sequences start with a backslash (\) followed by a special character, such as:

\n : newline
\t : tab
\' : single quote
\" : double quote
\\ : backslash
For example, if you want to include a new line in a string, you can use the \n escape sequence:
    string = "Hello,\nWorld!"
    print(string)
This will output:
    Hello,
    World!

Another example, if you want to include a single quote in a string that is enclosed in single quotes, you can use the \' escape sequence:
    string = 'I can\'t do this'
    print(string)
# This will output: I can't do this




Q33. How can you print the below string?

'iNeuron's Big Data Course'
Ans. 
    string='iNeuron\'s Big Data Course'
    print(string)
# output will be: iNeuron's Big Data Course




Q34. What is a list in Python?
Ans. A list in Python is a collection of items, which can be of different types (e.g. integers, strings, other lists, etc.). Lists are ordered, which means that the items in a list have a definite order and can be accessed by their index. 




Q35. How can you create a list in Python?
Ans. Lists are enclosed in square brackets [] and the items are separated by commas.
Here is an example of a list containing integers:
    numbers = [1, 2, 3, 4, 5]
And an example of a list containing strings:
    words = ['Hello', 'World', 'Python']




Q36. How can we access the elements in a list?
Ans.A list can also contain other lists, this is called nested lists.
    matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
to access the element 4 from the matrix, you can use the following code:
    print(matrix[1][0]) 
# Output: 4
It is important to note that indexing in python starts from 0, so the first element of the matrix will have the index [0][0], the second element [0][1] and so on.




Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
Ans. To access the word iNeuron from the list:
    lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
    result = lst[4][2]
    print(result)
# Output: iNeuron




Q38. Take a list as an input from the user and find the length of the list.
Ans. 
    lst = list(map(int, input("Enter a list of integers separated by space: ").split()))
    length = len(lst)
    print("The length of the list is: ",length)

list(map(int, input("Enter a list of integers separated by space: ").split())) is used to take the list of integers as input and then it maps the input function to the int function to convert the input values into integers.
len(lst) is used to find the length of the list.




Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]
Ans.  You can add the word "Big" in the 3rd index of the given list by using the list method insert(). The insert() method takes two arguments, the first one is the index where you want to insert the element and the second one is the element you want to insert. Here is an example:
    lst = ["Welcome", "to", "Data", "course"]
    lst.insert(2, "Big")
    print(lst)
# Outut: ['Welcome', 'to', 'Big', 'Data', 'course']
In this example, lst.insert(2, "Big") is used to insert the word "Big" at the 3rd index of the list. The first argument 2 is the index where you want to insert the element, and the second argument is the element you want to insert, which is "Big".




Q40. What is a tuple? How is it different from list?
Ans. A tuple in Python is a collection of items, similar to a list, but 
1. The items in a tuple are enclosed in parentheses () instead of square brackets []. Tuples are also ordered, which means that the items in a tuple have a definite order and can be accessed by their index.
2. The main difference between a list and a tuple is that a list is mutable, which means that you can change the elements of a list after it's created, using methods like append(), insert(), remove(), etc., while a tuple is immutable, which means that you cannot change the elements of a tuple after it's created.
3. Tuples are generally used to store values that should not be changed, such as coordinates or other fixed values.
4. Tuples are faster than lists and use less memory because of the immutability.




Q41. How can you create a tuple in Python?
Ans. Tuple are enclosed in parentheses () instead of square brackets [list].
Here is an example of a tuple containing integers:
    numbers = (1, 2, 3, 4, 5)
And an example of a tuple containing strings:
    words = ('Hello', 'World', 'Python')




Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
Ans. You can create a tuple but it is immutable, meaning you can't change the elements of a tuple after it's created, so you can't add elements to it directly. To add elements, you need to create a new tuple and concatenate the two tuples or convert the tuple to list, add elements and convert it back to tuple.
METHOD 1:-
    t = ('Ram', 'Mohan', 'Raj')
    my_name = ('Suresh',)
    t = t + my_name
    print(t)

METHOD 2:-
    t = ('Ram', 'Mohan', 'Raj')
    lst = list(t)
    lst.append('Suresh')
    t = tuple(lst)
    print(t)

# Output of both of them will be: ('Ram', 'Mohan', 'Raj', 'Suresh')




Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans. Yes, you can append two tuples by using the '+' operator. The + operator concatenates two tuples and creates a new tuple with the elements from both the tuples. Here is an example:
    t1 = (1, 2, 3)
    t2 = (4, 5, 6)
    t3 = t1 + t2
    print(t3)
# Output: (1, 2, 3, 4, 5, 6)




Q44. Take a tuple as an input and print the count of elements in it.
Ans. 
    t = tuple(map(int, input("Enter a tuple of integers separated by space: ").split()))
    count = len(t)
    print("The count of elements in the tuple is: ",count)




Q45. What are sets in Python?
Ans. A set in Python is a collection of unique items. Sets are enclosed in curly braces {} and the items are separated by commas. Sets are unordered, which means that the items in a set do not have a definite order and cannot be accessed by their index.
For ex:-
    numbers = {1, 2, 3, 4, 5}
    words = {'Hello', 'World', 'Python'}
One of the main characteristics of sets is that they only allow unique items, so, if you try to add a duplicate item to a set, it will not be added, and no error will be raised.




Q46. How can you create a set?
Ans. Sets are enclosed in curly braces {} and the items are separated by commas.
For ex:-
    numbers = {1, 2, 3, 4, 5}
    words = {'Hello', 'World', 'Python'}




Q47. Create a set and add "iNeuron" in your set.
Ans. 
    words = {'Hello', 'World', 'Python'}
    words.add(iNeuron)
    print(words)




Q48. Try to add multiple values using add() function.
Ans.
    s = {1,2,3}
# To add multiple values using add() function, you need to call the add() function multiple times
    s.add(4)
    s.add(5)
    s.add(6)
    print(s)
# Alternatively, you can also use the union operator | or the update() method to add multiple values to a set.
    s = {1, 2, 3}
    s |= {4, 5, 6}
    print(s)
# or 
    s = {1, 2, 3}
    s.update([4, 5, 6])
    print(s)
# Both of the above code snippets will give the output:- {1, 2, 3, 4, 5, 6}




Q49. How is update() different from add()?
Ans.update() is used to add multiple elements at once and it takes an iterable as an argument:-
    s = {1, 2, 3}
    s.update([4, 5, 6])
    print(s)  
# Output: {1, 2, 3, 4, 5, 6}
while add() method is used to add a single element and it takes one argument which is the element you want to add.
    s = {1, 2, 3}
    s.add(4)
    print(s)  
# Output: {1, 2, 3, 4}




Q50. What is clear() in sets?
Ans. The clear() method is used to remove all the elements from a set, making it an empty set. It does not take any arguments and does not return any value.
    s = {1, 2, 3}
    s.clear()
    print(s)  
# Output: set()



Q51. What is frozen set?
Ans. Frozen set is a built-in immutable version of set in python. It can only be created, not modified, and can be useful in situations where you need a set that cannot be modified.
Frozen sets are enclosed in curly braces {} and the items are separated by commas, just like sets.
Adding frozenset() is very necessary component.
For ex:-
    numbers = frozenset({1, 2, 3, 4, 5})
    words = frozenset({'Hello', 'World', 'Python'})




Q52. How is frozen set different from set?
Ans. Once a frozen set is created, its elements cannot be added, removed, or modified. In contrast, a regular set can be modified after it is created. Because frozen sets are immutable.




Q53. What is union() in sets? Explain via code.
Ans.Union() is a method in Python's set class that returns a new set containing all elements from the original set and all elements from one or more other sets.
For ex:-
# METHOD 1:-
# define two sets
set1 = {1, 2, 3}
set2 = {3, 4, 5}
# use union() to combine the sets
union_set = set1.union(set2)
print(union_set) 
# Output: {1, 2, 3, 4, 5}


# METHOD 2:-
# You can also use | operator for union of sets
    union_set = set1 | set2




Q54. What is intersection() in sets? Explain via code.
Ans. intersection() is a method in Python's set class that returns a new set containing only the elements that are common to all of the sets.

Here's an example:
# define two sets
    set1 = {1, 2, 3}
    set2 = {2, 3, 4}
# use intersection() to get the common elements
    intersection_set = set1.intersection(set2)
    print(intersection_set) 
# Output: {2, 3}
In this example, the intersection() method is called on set1, and set2 is passed as an argument. The resulting intersection_set contains only the elements that are present in both set1 and set2, which are 2 and 3.

# You can also use & operator for intersection of sets
    intersection_set = set1 & set2
# This will give the same result as intersection() method.




Q55. What is dictionary ibn Python?
Ans. A dictionary in Python is a collection of key-value pairs, where each key is unique. Dictionaries are unordered, which means that the items have no index and they are not in any particular order. They are also mutable, which means that you can add, remove, or modify items after the dictionary has been created.

Here's an example of a dictionary in Python:-
# create a dictionary
    my_dict = {'apple': 0.5, 'banana': 0.25, 'orange': 0.75}
# access the value for a given key
    print(my_dict['banana']) # Output: 0.25
# add a new key-value pair
    my_dict['pear'] = 0.3
# remove an item
    del my_dict['orange']
# iterate over keys
    for key in my_dict:
    print(key)

In this example, we create a dictionary called my_dict that contains three key-value pairs. We can access the value for a given key using the square brackets []. We can also add or remove key-value pairs using the del statement or the square brackets. You can also use the built-in methods like .items(), .keys(), .values() to access the elements of the dictionary.




Q56. How is dictionary different from all other data structures?
Ans. A dictionary in Python is a unique data structure that has several characteristics that distinguish it from other data structures:
1. Key-value pairs: Dictionaries store data in the form of key-value pairs, where each key is unique. This allows for efficient lookups of values based on their corresponding keys.
2. Unordered: Dictionaries are unordered, which means that the items have no index and they are not in any particular order. This is different from other data structures like lists and tuples, which have a specific order.
3. Mutable: Dictionaries are mutable, which means that you can add, remove, or modify items after the dictionary has been created. This is different from other data structures like sets and tuples, which are immutable and cannot be modified after they are created.
4. Hashing: Dictionary keys are hashed and stored in the memory, which provides a fast and efficient way to look up values based on their keys.
5. Fast Lookup: Dictionaries are optimized for fast lookups, making them suitable for scenarios where you need to perform many lookups on large datasets.
6. Flexibility: Dictionaries can hold different types of data and allow for easy implementation of different algorithms, such as counting, grouping, etc.
7. Ease of use: Dictionaries are easy to use, and you can use built-in functions like keys(), values(), items(), etc. to access the elements of the dictionary.




Q57. How can we delare a dictionary in Python?
Ans. 
1. Using curly braces {}: You can use curly braces {} to declare an empty dictionary or to initialize a dictionary with key-value pairs.
# empty dictionary
my_dict = {}
# dictionary with key-value pairs
my_dict = {'apple': 0.5, 'banana': 0.25, 'orange': 0.75}

2. Using the dict() constructor: You can use the dict() constructor to create a dictionary from an iterable of key-value pairs.
# dictionary from a list of tuples
my_dict = dict([('apple', 0.5), ('banana', 0.25), ('orange', 0.75)])
# dictionary from a set of tuples
my_dict = dict({('apple', 0.5), ('banana', 0.25), ('orange', 0.75)})

3. Using key-value pairs as function arguments: This way is also known as keyword arguments
my_dict = dict(apple=0.5, banana=0.25, orange=0.75)

4. Using dict comprehension: It is similar to list comprehension, but for dictionaries
my_dict = {key: value for key, value in [('apple', 0.5), ('banana', 0.25), ('orange', 0.75)]}




Q58. What will the output of the following?

var = {}
print(type(var))
Ans. 
# output will be:- <class 'dict'>
In this code, we are declaring an empty dictionary using curly braces {} and then using type() built-in function to check the data type of the variable var. As it is an empty dictionary, the type() function will return dict which is the data type for dictionary in python.




Q59. How can we add an element in a dictionary?
Ans. You can add a new key-value pair to a dictionary using the square brackets [] and the assignment operator =.

Here's an example:
    my_dict = {'apple': 0.5, 'banana': 0.25}
    my_dict['orange'] = 0.75
    print(my_dict)
# Output: {'apple': 0.5, 'banana': 0.25, 'orange': 0.75}

If the key already exists in the dictionary, the corresponding value will be updated.

# You can also use the update() method which allows you to add multiple key-value pairs to a dictionary.
    my_dict.update({'mango': 0.35, 'kiwi': 0.55})




Q60. Create a dictionary and access all the values in that dictionary.
Ans. 
    my_dict = {'apple': 0.7, 'banana': 0.2, 'orange': 0.9}
    values = my_dict.values()
    print(values)

# Output: dict_values([0.7, 0.2, 0.9])




Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans. 
# create a nested dictionary
    my_dict = {'fruits': {'apple': 0.5, 'banana': 0.25, 'orange': 0.75,'vegetables': {'carrot': 0.3, 'cucumber': 0.4, 'tomato': 0.6}}
    inner_dict = my_dict['fruits']
    print(inner_dict)

# Output: {'apple': 0.5, 'banana': 0.25, 'orange': 0.75}

In this example, we created a nested dictionary my_dict with two key-value pairs, where the values are inner dictionaries. To access the inner dictionary, we use the square brackets [] and the key name. In this case, we are accessing the inner dictionary 'fruits'. Then we are accessing all the elements in the inner dictionary by printing the inner_dict variable or by iterating over the inner_dict using items() method.




Q62. What is the use of get() function?
Ans. The get() function is a built-in method in Python's dictionary class that allows you to retrieve the value of a given key from a dictionary.
For ex:-
    my_dict = {'apple': 0.5, 'banana': 0.25, 'orange': 0.75}
# get the value for a given key
    value = my_dict.get('apple')
    print(value) 
# Output: 0.5

# get the value for a key that doesn't exist
    value = my_dict.get('pear', 0)
    print(value) 
# Output: 0




Q63. What is the use of items() function?
Ans. The items() function is used to return a view object that contains the key-value pairs of a dictionary. The view object contains the key-value pairs of the dictionary, as tuples in a list. The items() function is useful when you want to iterate over the key-value pairs of a dictionary. 
For ex.:-
    my_dict = {'a': 1, 'b': 2, 'c': 3}
    for key, value in my_dict.items():
        print(key, value)
# This will output:
    a 1
    b 2
    c 3
The items() method in python programming is used to return a view object that contains the key-value pairs of the given dictionary. The items() method returns the key-value pairs as tuple.




Q64. What is the use of pop() function?
Ans. The pop() function is used to remove and return an item from a dictionary, specified by its key. If the key is not found in the dictionary, an error (by default KeyError) will be raised. An optional second argument can be used to specify a default value to return if the key is not found. 
For example:
    my_dict = {'a': 1, 'b': 2, 'c': 3}
    value = my_dict.pop('b')
    print(value) 
# Output: 2
    print(my_dict)   
# Output: {'a': 1, 'c': 3}




Q65. What is the use of popitems() function?
Ans. The popitem() function is used to remove and return an arbitrary (random) key-value pair from a dictionary. It operates in a similar way to the pop() function, but instead of removing a specific item specified by its key, it removes and returns an arbitrary item.
    my_dict = {'a': 1, 'b': 2, 'c': 3}
    item = my_dict.popitem()
    print(item)  
# Output: ('c', 3)
    print(my_dict)  
# Output: {'a': 1, 'b': 2}
The popitem() method returns the key-value pair as tuple and removes the same from the dictionary.

Note that the order of the key-value pairs returned by popitem() is implementation-specific and may not be predictable. If you need to remove items in a specific order, you should use the pop() function or other methods to remove the desired items.




Q66. What is the use of keys() function?
Ans. The keys() function is used to return a view object that contains the keys of a dictionary. The view object contains the keys of the dictionary, as a list. The keys() function is useful when you want to iterate over the keys of a dictionary. Example:
    my_dict = {'a': 1, 'b': 2, 'c': 3}
    for key in my_dict.keys():
        print(key)
# This will output:
    a
    b
    c




Q67. What is the use of values() function?
Ans. The values() function is used to return a view object that contains the values of a dictionary. The view object contains the values of the dictionary, as a list. The values() function is useful when you want to iterate over the values of a dictionary. 
Example:
    my_dict = {'a': 1, 'b': 2, 'c': 3}
    for value in my_dict.values():
        print(value)
# This will output:
    1
    2
    3




Q68. What are loops in Python?
Ans.In Python, a loop is a control flow statement that allows you to iterate over a sequence (such as a list, tuple, or string) or other iterable objects (such as a dictionary or file). 
There are two types of loops in Python: the for loop and the while loop.
For example, to iterate over a list of numbers and print each one:(For loop)
    numbers = [1, 2, 3, 4, 5]
    for num in numbers:
        print(num)
# This will output:
    1
    2
    3
    4
    5

For example, to print the numbers from 1 to 5:(While loop)
    count = 1
    while count <= 5:
        print(count)
        count += 1
# This will output:
    1
    2
    3
    4
    5




Q69. How many type of loop are there in Python?
Ans. There are two types of loops in Python: 
1. The for loop 
2. The while loop.




Q70. What is the difference between for and while loops?
Ans. A for loop is used to iterate over a sequence of elements, such as a list, tuple, or string. The loop will execute the code block once for each element in the sequence, and automatically assigns the current element to a variable on each iteration. Once all elements have been processed, the loop will exit.

A while loop, on the other hand, is used to repeatedly execute a block of code as long as a certain condition is true. The loop will check the condition before each iteration, and if it is true, the code block will be executed. Once the condition is false, the loop will exit.




Q71. What is the use of continue statement?
Ans. The continue statement is used in loops to skip the current iteration and proceed with the next one. When a continue statement is encountered inside a loop, the current iteration is skipped, and the loop continues with the next iteration.

Here's an example of using the continue statement inside a for loop:
    for i in range(10):
        if i % 2 == 0: # check if the number is even
            continue # if the number is even, skip this iteration
        print(i)
# This will output:
    1
    3
    5
    7
    9
As you can see in the example above, the continue statement is used to skip the iteration if the number is even. This causes the print(i) statement to be skipped for even numbers, and only the odd numbers are printed.




Q72. What is the use of break statement?
Ans. The break statement is used in loops to immediately exit the loop and continue with the next statement after the loop. When a break statement is encountered inside a loop, the loop is immediately terminated and the program control resumes at the next statement after the loop.

Here's an example of using the break statement inside a for loop:
    for i in range(10):
        if i == 5:
            break
        print(i)
# This will output:
    0
    1
    2
    3
    4
As you can see in the example above, the break statement is used to exit the loop when the value of i is equal to 5. This causes the print(i) statement to be executed for the values of i from 0 to 4, and the loop exits when i is equal to 5.




Q73. What is the use of pass statement?
Ans. The pass statement in Python is used as a placeholder when a statement is required, but no action is needed. It is a null operation, and it does nothing. It is used as a placeholder for future code or as a way to silence the error for a code that hasn't been implemented yet.

Here's an example of using the pass statement inside a for loop:
    for i in range(10):
        if i % 2 == 0:
            pass
        else:
            print(i)
# This will output:
    1
    3
    5
    7
    9
As you can see in the example above, the pass statement is used as a placeholder for the code that should be executed when the value of i is even. This causes the print(i) statement to be executed for the odd values of i and nothing to happen for even values.




Q74. What is the use of range() function?
Ans. The range() function in Python is used to generate a sequence of numbers. It takes up to three arguments: start, stop, and step.

-> Start is the first number in the sequence, and it is an optional argument with a default value of 0.
-> Stop is the last number in the sequence, and it is a required argument.
-> Step is the difference between each number in the sequence, and it is an optional argument with a default value of 1.
-> The range() function generates numbers from start to stop-1 in increments of step.

Here are some examples of using the range() function:
1. Example 1:
# generate a range of numbers from 0 to 9
    for i in range(10):
        print(i)
# This will output:
    0
    1
    2
    3
    4
    5
    6
    7
    8
    9

2. Example 2:
# generate a range of numbers from 2 to 8
    for i in range(2, 9):
        print(i)
# This will output:
    2
    3
    4
    5
    6
    7
    8




Q75. How can you loop over a dictionary?
Ans. There are multiple ways to iterate over a dictionary in Python.

1. Access key using the build .keys() 
2. Access key without using a key() 
3. Iterate through all values using .values()
4. Iterate through all key, and value pairs using items()
5. Access both key and value without using items()
6. Print items in Key-Value in pair 




# Coding problems




Q76. Write a Python program to find the factorial of a given number.
Ans. 
    def factorial(n):
        if n == 0:
            return 1
        else:
            return n * factorial(n-1)

    num = 5
    print("The factorial of", num, "is", factorial(num))

In the last line of the code, the variable num is set to 5 and the program prints the factorial of num by calling the factorial function and passing in num as an argument. The output will be The factorial of 5 is 120.





Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
Ans. 
    def simple_interest(principal, rate, time):
            si = (principal * rate * time) / 100
            return si
    p = int(input("Enter a principle amount: "))
    r = int(input("Enter a rate of interest: "))
    t = int(input("Enter a time(in years): "))
    result = simple_interest(p, r, t)
    print("Simple Interest is: ", result)




Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Ans. 
    def compound_interest(principal, rate, time):
        return principal * (pow((1 + rate / 100), time))

    principal = int(input("Enter a principle amount: "))
    rate = int(input("Enter a rate of interest: "))
    time = int(input("Enter a time(in years): "))

    amount = compound_interest(principal, rate, time)

    print("Compound Interest: ", amount - principal)




Q79. Write a Python program to check if a number is prime or not.
Ans. 
    def is_prime(num):
        if num > 1:
            for i in range(2,num):
                if (num % i) == 0:
                    return False
            else:
                return True
        else:
            return False

    num = int(input("Enter the no. you want to check: "))
    if is_prime(num):
        print(num,"is a prime number")
    else:
        print(num,"is not a prime number")




Q80. Write a Python program to check Armstrong Number.
Ans. An Armstrong number (also known as a narcissistic number) is a number that is equal to the sum of its own digits each raised to the power of the number of digits.

    def is_armstrong(num):
        n = len(str(num))
        temp = num
        sum = 0
        while temp > 0:
            digit = temp % 10
            sum += digit ** n
            temp //= 10
        return num == sum

    num = int(input("Enter the no. you want to check: "))
    if is_armstrong(num):
        print(num, "is an Armstrong number.")
    else:
        print(num, "is not an Armstrong number.")




Q81. Write a Python program to find the n-th Fibonacci Number.
Ans. The Fibonacci sequence is a series of numbers in which each number is the sum of the two preceding ones.

    def fibonacci(n):
        if n <= 0:
            return 0
        elif n == 1:
            return 1
        else:
            return fibonacci(n-1) + fibonacci(n-2)

    num = int(input("Enter the nth no. you want to check: "))
    print("The", num, "th Fibonacci number is:", fibonacci(num))




Q82. Write a Python program to interchange the first and last element in a list.
Ans. 
    def interchange_first_last(lst):
        lst[0], lst[-1] = lst[-1], lst[0]
        return lst

    my_list = print("Enter the 5 no. to do the program: ")
    a=int(input("Enter the first no.: "))
    b=int(input("Enter the second no.: "))
    c=int(input("Enter the third no.: "))
    d=int(input("Enter the forth no.: "))
    e=int(input("Enter the fifth no.: "))

    my_list=[a,b,c,d,e]
    print("Original list:", my_list)

    my_list = interchange_first_last(my_list)
    print("List after interchanging first and last elements:", my_list)




Q83. Write a Python program to swap two elements in a list.
Ans. 
def swap_elements(lst, index1, index2):
    lst[index1], lst[index2] = lst[index2], lst[index1]
    return lst

my_list = print("Enter the 5 no. to do the program: ")
a=int(input("Enter the first no.: "))
b=int(input("Enter the second no.: "))
c=int(input("Enter the third no.: "))
d=int(input("Enter the forth no.: "))
e=int(input("Enter the fifth no.: "))
my_list=[a,b,c,d,e]
print("Original list:", my_list)

my_list = swap_elements(my_list, 1, 3)
print("List after swapping elements:", my_list)




Q84. Write a Python program to find N largest element from a list.
Ans. 
    def n_largest(lst, n):
        return sorted(lst, reverse=True)[:n]

    my_list = [1, 3, 5, 2, 4, 8, 10, 6, 9, 7]
    n = int(input("What nth largest element you want to find out? : "))
    print("Original list:", my_list)

    largest_n = n_largest(my_list, n)
    print(f"{n} largest element from the list:", largest_n)




Q85. Write a Python program to find cumulative sum of a list.
Ans. 
    def cumulative_sum(lst):
        cum_sum = [lst[0]]
        for i in range(1, len(lst)):
            cum_sum.append(cum_sum[i-1] + lst[i])
        return cum_sum

    my_list = print("Enter the 5 no. to do the program: ")
    a=int(input("Enter the first no.: "))
    b=int(input("Enter the second no.: "))
    c=int(input("Enter the third no.: "))
    d=int(input("Enter the forth no.: "))
    e=int(input("Enter the fifth no.: "))
    my_list=[a,b,c,d,e]
    print("Original list:", my_list)

    cumulative_list = cumulative_sum(my_list)
    print("Cumulative sum of the list:", cumulative_list)




Q86. Write a Python program to check if a string is palindrome or not.
Ans. 
def is_palindrome(s):
    return s == s[::-1]

string = input("Enter the string: ")
if is_palindrome(string):
    print(string, "is a palindrome.")
else:
    print(string, "is not a palindrome.")




Q87. Write a Python program to remove i'th element from a string.
Ans.
def remove_ith_char(s, i):
    return s[:i] + s[i+1:]

string = "Hello World!"
i = int(input("Enter the i'th element which you want to remove: "))
print("Original String: ", string)

new_string = remove_ith_char(string, i)
print("String after removing the", i, "th character: ", new_string)




Q88. Write a Python program to check if a substring is present in a given string.
Ans. 
def is_substring(string, sub_string):
    return sub_string in string

string = "Hello World!"
sub_string = (input("Enter the sub string you want to check: "))

if is_substring(string, sub_string):
    print(sub_string, "is present in", string)
else:
    print(sub_string, "is not present in", string)




Q89. Write a Python program to find words which are greater than given length k.
Ans. 
    def greater_than_k(string, k):
        words = string.split()
        greater_words = []
        for word in words:
            if len(word) > k:
                greater_words.append(word)
        return greater_words

    string = input("Enter the string: ")
    k = int(input("Enter the length k of the characters: "))

    greater_words = greater_than_k(string, k)
    print("Words greater than length", k, "in the string are:", greater_words)




Q90. Write a Python program to extract unique dictionary values.
Ans. 
    def unique_values(d):
        return list(set(d.values()))

    my_dict = {
        "a": 1,
        "b": 2,
        "c": 3,
        "d": 2
    }
    print("Original dictionary:", my_dict)

    unique_values_list = unique_values(my_dict)
    print("Unique values in the dictionary:", unique_values_list)




Q91. Write a Python program to merge two dictionary.
Ans. 
    def merge_dictionaries(dict1, dict2):
        return {**dict1, **dict2}

    dict1 = {'a': 1, 'b': 2}
    dict2 = {'c': 3, 'd': 4}

    merged_dict = merge_dictionaries(dict1, dict2)
    print("Merged dictionary:", merged_dict)




Q92. Write a Python program to convert a list of tuples into dictionary.
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Ans.
    def list_to_dict(list_of_tuples):
        return dict(list_of_tuples)

    list_of_tuples = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]

    converted_dict = list_to_dict(list_of_tuples)
    print("Converted dictionary:", converted_dict)




Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Ans.
    def number_and_cube(lst):
        return [(x, x**3) for x in lst]

    lst = [9, 5, 6]

    list_of_tuples = number_and_cube(lst)
    print("List of tuples:", list_of_tuples)




Q94. Write a Python program to get all combinations of 2 tuples.
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Ans.
    from itertools import product
    def get_combinations(tuple1, tuple2):
        return list(product(tuple1, tuple2))

    test_tuple1 = (7, 2)
    test_tuple2 = (7, 8)

    combinations = get_combinations(test_tuple1, test_tuple2)
    print("All combinations of 2 tuples:", combinations)




Q95. Write a Python program to sort a list of tuples by second item.
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Ans. 
    def sort_by_second(list_of_tuples):
        return sorted(list_of_tuples, key=lambda x: x[1])

    list_of_tuples = [('for', 24), ('Geeks', 8), ('Geeks', 30)]

    sorted_list = sort_by_second(list_of_tuples)
    print("Sorted list of tuples by second item:", sorted_list)




Q96. Write a python program to print below pattern.
* 
* * 
* * * 
* * * * 
* * * * * 
Ans.
    for i in range(1, 6):
        print("* " * i)




Q97. Write a python program to print below pattern.
    *
   **
  ***
 ****
*****
Ans. 
    for i in range(1, 6):
        print(" " * (5-i) + "*" * i)




Q98. Write a python program to print below pattern.
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Ans. 
    size = 5
    m = (2 * size) - 2
    for i in range(0, size):
        for j in range(0, m):
            print(end=" ")
        m = m - 1
        for j in range(0, i + 1):
            print("* ", end=' ')
        print(" ")




Q99. Write a python program to print below pattern.
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Ans. 
rows = 5
    for i in range(1, rows + 1):
        for j in range(1, i + 1):
            print(j, end=' ')
        print('')




Q100. Write a python program to print below pattern.
A 
B B 
C C C 
D D D D 
E E E E E 
Ans. 
    n = 5
    a=65
    for i in range(1,n+1):
        for j in range(1, i+1):
            print("%c" %(a), end="")
        a +=1
        print()