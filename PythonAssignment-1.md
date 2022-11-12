## Assignment Part-1
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