Q1. Why do we call Python as a general-purpose and high-level programming language?

Python is called a general-purpose programming language because it can be used to develop a wide range of 

applications in different domains, such as web development, machine learning, data analysis, scientific 

computing, game development, etc. It provides support for multiple programming paradigms, including 

object-oriented, procedural, and functional programming, making it flexible and adaptable for different use 

cases. Python is also considered a high-level programming language because it provides high-level data 

structures, such as lists, dictionaries, and sets, and abstracts away many low-level details of the underlying 

hardware and operating system. This makes it easier for developers to write code that is more concise, 

readable, and maintainable, without worrying about memory management or other low-level optimizations.

Q2. Why is Python called a dynamically typed language?

Python is called a dynamically typed language because the type of a variable is determined at runtime, not at 

compile-time. In other words, you don't need to specify the data type of a variable explicitly when you declare 

it. Instead, Python infers the type of the variable based on the value assigned to it. This makes Python very 

flexible and allows you to write code that can handle a wide range of data types without having to worry about 

type errors.

Q3. List some pros and cons of the Python programming language?

Pros:

Easy to learn and use
Large standard library and third-party packages
Multi-paradigm programming language
Platform-independent
Good for rapid prototyping and development
Supports both object-oriented and procedural programming
Provides interactive shell for testing and experimentation
Cons:

Slow compared to compiled languages
Not ideal for memory-intensive tasks
Global interpreter lock (GIL) can cause performance issues in multi-threaded applications
Less suitable for low-level programming
Dynamic typing can make it harder to catch certain types of errors
Not a good choice for real-time systems

Q4. In what all domains can we use Python?

Python can be used in a wide range of domains, some of which include:

Web development: Django, Flask, Pyramid, etc.
Machine learning and artificial intelligence: TensorFlow, PyTorch, Keras, scikit-learn, etc.
Data analysis and visualization: pandas, NumPy, Matplotlib, Seaborn, etc.
Scientific computing and numerical analysis: SciPy, SymPy, etc.
Game development: Pygame, Panda3D, etc.
Desktop application development: PyQt, PyGTK, etc.
Network programming: Twisted, Scapy, etc.
System administration and automation: Fabric, Ansible, etc.

Q5. What are variables, and how can we declare them?

In Python, a variable is a named location in memory that is used to store a value. You can think of a variable as 

a container that holds a value of a particular data type, such as an integer, float, string, etc.

To declare a variable in Python, you simply choose a name for the variable and assign a value to it using the 

equal (=) sign. 
Q6. To take input from the user in Python, we can use the input() function. Here is an example:


name = input("Enter your name: ")
print("Hello, " + name + "!")
In this example, the input() function is used to prompt the user to enter their name, and the value entered by 

the user is stored in the variable 'name'.

Q7. The default datatype of the value that has been taken as an input using input() function is a string. This 

means that if the user enters a number, it will be treated as a string, and not as a numerical value.

Q8. Type casting is the process of converting one data type into another. In Python, we can use built-in 

functions like int(), float(), str(), etc. to perform type casting. Here's an example:

# Convert a string to an integer
a = "10"
b = int(a)
print(b)

# Convert an integer to a string
c = 20
d = str(c)
print(d)
Q9. Yes, we can take more than one input from the user using a single input() function by separating the 

inputs with commas. Here's an example:

name, age = input("Enter your name and age: ").split()
print("Your name is " + name + " and your age is " + age + ".")
In this example, the input() function is used to prompt the user to enter their name and age, separated by a 

space. The split() function is used to split the input string into two separate values, which are then assigned to 

the variables 'name' and 'age'.

Q10. Keywords are reserved words in Python that have a special meaning and cannot be used as variable 

names or function names. Some examples of keywords in Python include 'if', 'else', 'for', 'while', 'and', 'or', 

'not', 'class', 'def', 'return', 'import', 'from', 'as', 'global', 'try', 'except', 'finally', 'raise', 'assert', 'with', and 

'lambda'.

Q11. No, we cannot use keywords as a variable in Python. Keywords are reserved words in Python that have a 

specific meaning and purpose in the language. Using keywords as variable names will result in a syntax error. 

For example, if we try to use the keyword 'if' as a variable name, we will get an error like this: "SyntaxError: 

invalid syntax".

Q12. Indentation is a way of structuring code in Python by using whitespace at the beginning of a line to 

indicate a block of code. The use of indentation is mandatory in Python, and it is used to define the scope of 

loops, functions, conditional statements, and other control flow structures. It makes the code more readable 

and helps to avoid errors in the code.

Q13. We can throw some output in Python by using the print() function. The print() function takes one or more 

arguments and prints them to the console or terminal. For example, we can use the print() function to display 

a string like "Hello, World!" as follows:

bash

print("Hello, World!")
Q14. Operators in Python are symbols or special keywords that perform arithmetic or logical operations on 

operands. There are several types of operators in Python, including arithmetic operators (+, -, *, /, %, **), 

comparison operators (==, !=, >, <, >=, <=), logical operators (and, or, not), bitwise operators (&, |, ^, ~), 

and assignment operators (=, +=, -=, *=, /=, %=, **=, //=).

Q15. The '/' operator performs floating-point division, which returns a float value, while the '//' operator 

performs integer division, which returns an integer value. For example:


>>> 7 / 3
2.3333333333333335

>>> 7 // 3
2
In the first example, the result is a float value, while in the second example, the result is an integer value (the 

floor of the division).

Q16. Here's the code to produce the desired output:


print("iNeuron" * 4)
Output:


iNeuroniNeuroniNeuroniNeuron
Q17. Here's the code to take a number as an input from the user and check if the number is odd or even:


num = int(input("Enter a number: "))
if num % 2 == 0:
    print(num, "is even")
else:
    print(num, "is odd")
Q18. Boolean operators are operators that operate on boolean values, i.e., True or False. There are three 

boolean operators in Python: and, or, and not.

Q19. The output of the following will be:

1 or 0 evaluates to 1 because the or operator returns the first operand if it is true, otherwise it returns the 

second operand. In this case, 1 is true, so the expression returns 1.
0 and 0 evaluates to 0 because the and operator returns the first operand if it is false, otherwise it returns the 

second operand. In this case, both operands are false, so the expression returns 0.
True and False and True evaluates to False because the and operator returns the first operand if it is false, 

otherwise it returns the second operand. In this case, the first two operands are True and False, respectively, 

so the expression returns False.
1 or 0 or 0 evaluates to 1 because the or operator returns the first operand if it is true, otherwise it returns the 

second operand. In this case, the first operand is true, so the expression returns 1.

Q20. Conditional statements are used to make decisions in a program based on whether a certain condition is 

true or false. The two main types of conditional statements in Python are if statements and if-else statements. 

The if statement is used to execute a block of code if a certain condition is true. The if-else statement is used to 

execute one block of code if a certain condition is true, and another block of code if the condition is false. The 

if-elif-else statement can be used to execute one of several blocks of code depending on the value of multiple 

conditions.

Q21. The 'if', 'elif', and 'else' keywords are used for conditional execution in Python.

'if' is used to test a condition and execute the code inside the block only if the condition is true.
'elif' (short for "else if") is used to test additional conditions, after the 'if' block, and execute the code inside the 

block of the first condition that is true.
'else' is used to execute a block of code if none of the conditions are true.
Q22. Here's the code to take the age of a person as input and display "I can vote" if the age is greater than or 

equal to 18, and "I can't vote" if the age is less than 18:

python
Copy code
age = int(input("Enter your age: "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")
Q23. Here's the code to display the sum of all even numbers from the given list:

bash
Copy code
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for num in numbers:
    if num % 2 == 0:
        sum += num
print("Sum of even numbers:", sum)
Output:

mathematica
Copy code
Sum of even numbers: 392
Q24. Here's the code to take 3 numbers as input from the user and display the greatest number as output:

python
Copy code
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
num3 = int(input("Enter the third number: "))

if num1 > num2 and num1 > num3:
    print(num1, "is the greatest number")
elif num2 > num3:
    print(num2, "is the greatest number")
else:
    print(num3, "is the greatest number")
Q25. Here's the code to display only those numbers from a list that satisfy the given conditions:

bash
Copy code
numbers = [12, 75, 150, 180, 145, 525, 50]

for num in numbers:
    if num > 500:
        break
    elif num > 150:
        continue
    elif num % 5 == 0:
        print(num)
Output:

Copy code
75
50

Q26. In Python, a string is a sequence of characters enclosed in quotation marks (either single or double). Strings are immutable objects, which means that once a string is created, it cannot be modified. We can declare a string in Python by simply assigning a value enclosed in quotation marks to a variable, like this:

python
Copy code
my_string = "Hello, world!"
Q27. We can access a string using its index by specifying the index value within square brackets next to the string variable. The index value starts from 0 for the first character in the string and increases by 1 for each subsequent character. For example:

python
Copy code
my_string = "Hello, world!"
print(my_string[0])   # Output: H
print(my_string[1])   # Output: e
print(my_string[-1])  # Output: !
Q28. Here is the code to get the desired output:

python
Copy code
string = "Big Data iNeuron"
desired_output = string[9:]
print(desired_output)  # Output: iNeuron
Q29. Here is the code to get the desired output:

python
Copy code
string = "Big Data iNeuron"
desired_output = string[-7::-1]
print(desired_output)  # Output: norueNi
Q30. To reverse the string given in the above question, we can use slicing with a step of -1:

python
Copy code
string = "Big Data iNeuron"
reversed_string = string[::-1]
print(reversed_string)  # Output: norueNi ataD giB

Q31. We cannot delete an entire string at once in Python since strings are immutable. Once created, the string's value cannot be changed or deleted. We can only delete a string variable using the del keyword.

Q32. An escape sequence is a combination of characters that represents a special character, such as a newline or tab, that cannot be directly typed in a string. Escape sequences are represented with a backslash \ followed by a specific character, such as \n for a newline or \t for a tab.

Q33. We can print the below string in Python by using double quotes ("), single quotes ('), or by escaping the single quote within the string using a backslash (\):

python
Copy code
print("iNeuron's Big Data Course")  # Output: iNeuron's Big Data Course
print('iNeuron\'s Big Data Course')  # Output: iNeuron's Big Data Course
Q34. In Python, a list is an ordered collection of elements that can be of any data type. Lists are mutable, which means that we can modify the elements in a list after it has been created. We can also add or remove elements from a list as needed.

Q35. We can create a list in Python by enclosing a comma-separated sequence of elements within square brackets ([]). Here is an example:

python
Copy code
my_list = [1, 2, 3, "four", 5.0]
print(my_list)  # Output: [1, 2, 3, 'four', 5.0]

Q36. We can access the elements in a list by using the index value of the element within square brackets next to the list variable. The index value starts from 0 for the first element in the list and increases by 1 for each subsequent element. We can also access a sublist within a list using slicing. For example:

python
Copy code
my_list = [1, 2, 3, "four", 5.0]
print(my_list[0])        # Output: 1
print(my_list[3])        # Output: four
print(my_list[1:4])      # Output: [2, 3, 'four']
print(my_list[-2:])      # Output: ['four', 5.0]
Q37. Here is the code to access the word "iNeuron" from the given list:

python
Copy code
lst = [1, 2, 3, "Hi", [45, 54, "iNeuron"], "Big Data"]
print(lst[4][2])   # Output: iNeuron
Q38. Here is the code to take a list as input from the user and find its length:

python
Copy code
my_list = input("Enter elements of list separated by commas: ").split(",")
length = len(my_list)
print("The length of the list is", length)
Q39. Here is the code to add the word "Big" in the 3rd index of the given list:

python
Copy code
lst = ["Welcome", "to", "Data", "course"]
lst.insert(3, "Big")
print(lst)  # Output: ['Welcome', 'to', 'Data', 'Big', 'course']
Q40. In Python, a tuple is an ordered collection of elements, similar to a list. However, tuples are immutable, which means that once a tuple is created, its elements cannot be modified. We can create a tuple in Python by enclosing a comma-separated sequence of elements within parentheses (()). Here is an example:

python
Copy code
my_tuple = (1, 2, 3, "four", 5.0)
print(my_tuple)  # Output: (1, 2, 3, 'four', 5.0)
The main difference between a tuple and a list is that a tuple is immutable, whereas a list is mutable. Tuples are also generally faster and more memory-efficient than lists, but they have fewer built-in methods and functions.

Q41. In Python, we can create a tuple by enclosing a comma-separated sequence of elements within parentheses (()). Here is an example:

python
Copy code
my_tuple = (1, 2, 3, "four", 5.0)
print(my_tuple)  # Output: (1, 2, 3, 'four', 5.0)
Q42. No, we cannot add an element to a tuple because tuples are immutable. Once a tuple is created, its elements cannot be modified. We can only create a new tuple with the desired elements. Here is an example:

python
Copy code
my_tuple = (1, 2, 3, "four", 5.0)
new_tuple = my_tuple + ("John",)
print(new_tuple)  # Output: (1, 2, 3, 'four', 5.0, 'John')
In this example, we created a new tuple by concatenating the original tuple my_tuple with a new tuple containing the string "John". The resulting tuple new_tuple contains all the elements of my_tuple followed by the string "John".

Q43. No, we cannot append two tuples together using the append() method because tuples are immutable. However, we can concatenate two tuples together using the + operator to create a new tuple that contains all the elements of both tuples. Here is an example:

python
Copy code
tuple1 = (1, 2, 3)
tuple2 = ("four", "five", "six")
new_tuple = tuple1 + tuple2
print(new_tuple)  # Output: (1, 2, 3, 'four', 'five', 'six')
Q44. Here is the code to take a tuple as input from the user and print the count of elements in it:

python
Copy code
my_tuple = tuple(input("Enter elements of tuple separated by commas: ").split(","))
count = len(my_tuple)
print("The count of elements in the tuple is", count)
Q45. In Python, a set is an unordered collection of unique elements. Sets are similar to lists and tuples, but they do not have any duplicate elements. We can create a set in Python by enclosing a comma-separated sequence of elements within curly braces ({}). Here is an example:

python
Copy code
my_set = {1, 2, 3, "four", 5.0}
print(my_set)  # Output: {1, 2, 3, 'four', 5.0}
We can also create a set from a list or tuple using the set() function. Here is an example:

python
Copy code
my_list = [1, 2, 3, "four", 5.0, 1, 2, "four"]
my_set = set(my_list)
print(my_set)  # Output: {1, 2, 3, 'four', 5.0}
In this example, the original list my_list contains some duplicate elements, but when we create a set from it using the set() function, the resulting set my_set contains only the unique elements.

Q45. In Python, a set is an unordered collection of unique elements. Sets are similar to lists and tuples, but they do not have any duplicate elements.

Q46. We can create a set in Python by enclosing a comma-separated sequence of elements within curly braces ({}). Here is an example:

python
Copy code
my_set = {1, 2, 3, "four", 5.0}
print(my_set)  # Output: {1, 2, 3, 'four', 5.0}
We can also create a set from a list or tuple using the set() function. Here is an example:

python
Copy code
my_list = [1, 2, 3, "four", 5.0, 1, 2, "four"]
my_set = set(my_list)
print(my_set)  # Output: {1, 2, 3, 'four', 5.0}
In this example, the original list my_list contains some duplicate elements, but when we create a set from it using the set() function, the resulting set my_set contains only the unique elements.

Q47. Here is the code to create a set and add "iNeuron" to it:

python
Copy code
my_set = {1, 2, 3, "four", 5.0}
my_set.add("iNeuron")
print(my_set)  # Output: {1, 2, 3, 'four', 5.0, 'iNeuron'}
Q48. We can add multiple values to a set using the update() function. The update() function takes an iterable as its argument, such as a list or another set. Here is an example:

python
Copy code
my_set = {1, 2, 3, "four", 5.0}
my_set.update(["iNeuron", 6, 7])
print(my_set)  # Output: {1, 2, 3, 'four', 5.0, 'iNeuron', 6, 7}
In this example, we used the update() function to add the elements "iNeuron", 6, and 7 to the set my_set.

Q49. The add() function is used to add a single element to a set, while the update() function is used to add multiple elements to a set. Additionally, the update() function can take any iterable as its argument, such as a list or another set, while the add() function can only take a single element as its argument.

Q50. The clear() function in sets is used to remove all the elements from a set. After the clear() function is called, the set becomes empty. Here is an example:

python
Copy code
my_set = {1, 2, 3, "four", 5.0}
my_set.clear()
print(my_set)  # Output: set()
In this example, we used the clear() function to remove all the elements from the set my_set.

Q51. What is frozen set in Python?

A frozen set in Python is an immutable version of a set. It is created using the frozenset() constructor, and once created, its elements cannot be modified. This means that a frozen set is a set that cannot be changed once it has been created.

Frozen sets are useful in situations where you need to create a set of values that will not change, such as a set of constants or a set of configuration values that should not be modified at runtime.

Frozen sets support all the standard set operations, such as union, intersection, and difference, but they cannot be modified using methods like add(), remove(), or discard(). This means that frozen sets are less flexible than regular sets, but they are also more efficient in terms of memory usage and can be used in situations where immutability is important.

Q52. How is a frozen set different from a set in Python?

The main difference between a frozen set and a regular set in Python is that a frozen set is immutable, meaning its elements cannot be added, removed or modified once it has been created, while a regular set is mutable and can be modified after creation.

Another difference is that frozen sets are hashable, meaning they can be used as elements in other sets, dictionaries, or as keys in dictionaries. Regular sets, on the other hand, are not hashable because they are mutable, and therefore cannot be used as elements in other sets or as keys in dictionaries.

In terms of functionality, frozen sets support all the same set operations as regular sets, such as union, intersection, difference, and symmetric difference. However, since frozen sets cannot be modified, methods that modify sets such as add(), remove() or discard() are not available for frozen sets.

Overall, frozen sets are useful when you need a set of elements that cannot be modified, and that can be used as elements in other sets or as keys in dictionaries.

Q53. What is union() in sets? Explain via code.

In sets, the union() method returns a set containing all the unique elements of both sets. In other words, it combines the elements of both sets and removes any duplicates. The union() method can be called using the | operator or the union() method.

Here is an example code that demonstrates the use of union() method:

makefile
Copy code
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
set3 = set1.union(set2)
print(set3)
# Output: {1, 2, 3, 4, 5, 6, 7, 8}
In the example above, we have two sets, set1 and set2, which have some overlapping elements. We use the union() method to combine the elements of both sets, and assign the result to set3. The resulting set, set3, contains all the unique elements of both sets.

Q54. What is intersection() in sets? Explain via code.

In sets, the intersection() method returns a set that contains the common elements of both sets. In other words, it returns a set containing the elements that are present in both sets. The intersection() method can be called using the & operator or the intersection() method.

Here is an example code that demonstrates the use of intersection() method:

makefile
Copy code
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
set3 = set1.intersection(set2)
print(set3)
# Output: {4, 5}
In the example above, we have two sets, set1 and set2, which have some overlapping elements. We use the intersection() method to find the common elements between the two sets, and assign the result to set3. The resulting set, set3, contains only the elements that are present in both sets.

Q56. How is dictionary different from all other data structures?

A dictionary in Python is a collection of key-value pairs, where each key is unique and used to access its corresponding value. It differs from other data structures in that it does not store its elements in a sequence or order. Instead, it allows us to access its values based on their associated keys, making it a useful tool for organizing and retrieving information in a structured way.

Q57. How can we declare a dictionary in Python?

We can declare a dictionary in Python by enclosing a comma-separated list of key-value pairs within curly braces {}. Each key-value pair is separated by a colon :.

For example:

arduino
Copy code
my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
Q58. What will the output of the following?

go
Copy code
var = {}
print(type(var))
Output: <class 'dict'>

The code creates an empty dictionary and then prints the type of the variable var. Since var is a dictionary, the output will be <class 'dict'>.

Q59. How can we add an element in a dictionary?

We can add an element to a dictionary by assigning a value to a new or existing key in the dictionary. For example:

bash
Copy code
my_dict = {'key1': 'value1', 'key2': 'value2'}
my_dict['key3'] = 'value3'  # add new key-value pair
my_dict['key1'] = 'new_value1'  # update an existing key's value
In the first line, we create a dictionary with two key-value pairs. We then add a new key-value pair to the dictionary by assigning the value 'value3' to the new key 'key3'. Finally, we update the value associated with the existing key 'key1' to 'new_value1'.

Q60. Create a dictionary and access all the values in that dictionary.

We can access all the values in a dictionary by using the values() method, which returns a list-like object containing all the values in the dictionary. For example:

sql
Copy code
my_dict = {'name': 'John', 'age': 30, 'city': 'New York'}

# access all values using values() method
values = my_dict.values()
print(values)  # output: dict_values(['John', 30, 'New York'])
Alternatively, we can also access the values of individual keys in the dictionary by using square brackets [] and passing in the key as an argument. For example:

bash
Copy code
my_dict = {'name': 'John', 'age': 30, 'city': 'New York'}

# access individual values using keys
name = my_dict['name']
age = my_dict['age']
city = my_dict['city']

print(name, age, city)  # output: John 30 New York


Q61. Create a nested dictionary and access all the element in the inner dictionary.

Ans: Here's an example of a nested dictionary and how to access elements in the inner dictionary:

bash
Copy code
my_dict = {
    "person1": {
        "name": "John",
        "age": 30,
        "city": "New York"
    },
    "person2": {
        "name": "Jane",
        "age": 25,
        "city": "London"
    }
}

# Accessing the elements in the inner dictionary
print(my_dict["person1"]["name"])  # Output: John
print(my_dict["person2"]["age"])   # Output: 25
Q62. What is the use of get() function?

Ans: The get() function is used to access the value of a key in a dictionary. It takes a key as its argument and returns the value associated with that key. If the key is not found in the dictionary, it returns None (by default), or a specified value. Here's an example:

bash
Copy code
my_dict = {"apple": 3, "banana": 5, "orange": 2}

# Accessing the value of a key using get() function
print(my_dict.get("apple"))     # Output: 3

# Specifying a default value to be returned if key not found
print(my_dict.get("grapes", 0)) # Output: 0
Q63. What is the use of items() function?

Ans: The items() function is used to return a view object containing the key-value pairs of a dictionary as tuples. This view object can then be used to iterate over the dictionary's items. Here's an example:

bash
Copy code
my_dict = {"apple": 3, "banana": 5, "orange": 2}

# Using items() function to iterate over the key-value pairs
for key, value in my_dict.items():
    print(key, ":", value)

# Output:
# apple : 3
# banana : 5
# orange : 2
Q64. What is the use of pop() function?

Ans: The pop() function is used to remove a key-value pair from a dictionary and return the value associated with the key. It takes a key as its argument and returns the corresponding value. If the key is not found in the dictionary, it raises a KeyError (by default), or a specified value. Here's an example:

bash
Copy code
my_dict = {"apple": 3, "banana": 5, "orange": 2}

# Removing a key-value pair using pop() function
value = my_dict.pop("banana")
print(value)                  # Output: 5
print(my_dict)                # Output: {"apple": 3, "orange": 2}

# Specifying a default value to be returned if key not found
value = my_dict.pop("grapes", 0)
print(value)                  # Output: 0
Q65. What is the use of popitems() function?

Ans: The popitem() function is used to remove and return an arbitrary key-value pair from a dictionary as a tuple. This function can be useful when you want to remove and process items from a dictionary in an arbitrary order. Here's an example:

bash
Copy code
my_dict = {"apple": 3, "banana": 5, "orange": 2}

# Removing and returning an arbitrary key-value pair using popitem() function
key, value = my_dict.popitem()
print(key, ":", value)         # Output: orange : 2
print(my_dict)                # Output

Q66. The keys() function in Python is used to return a view object that contains the keys of a dictionary.

The syntax for keys() function is:

scss
Copy code
dictionary.keys()
Example:

perl
Copy code
my_dict = {1:'apple', 2:'ball', 3:'cat'}
keys = my_dict.keys()
print(keys)
Output:

scss
Copy code
dict_keys([1, 2, 3])
Here, keys is a view object containing the keys of the dictionary my_dict. We can use this object to iterate over the keys of the dictionary.

Q67. The values() function in Python is used to return a view object that contains the values of a dictionary.

The syntax for values() function is:

scss
Copy code
dictionary.values()
Example:

perl
Copy code
my_dict = {1:'apple', 2:'ball', 3:'cat'}
values = my_dict.values()
print(values)
Output:

css
Copy code
dict_values(['apple', 'ball', 'cat'])
Here, values is a view object containing the values of the dictionary my_dict. We can use this object to iterate over the values of the dictionary.

Q68. Loops in Python are used to execute a block of code repeatedly as long as the specified condition is true.

Q69. There are two types of loops in Python:

for loop
while loop
Q70. The main difference between for and while loops in Python is the way they iterate over a sequence of values. A for loop is used to iterate over a sequence of values, such as a list, tuple, or string. It runs for a predetermined number of times, which is the length of the sequence. On the other hand, a while loop is used to execute a block of code repeatedly as long as a specified condition is true. The loop continues to run until the condition becomes false.

Q71. The continue statement is used to skip the current iteration of a loop and move to the next iteration. It is commonly used in loops to skip over certain elements based on a condition.

Here's an example of using continue statement:

bash
Copy code
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]

for num in numbers:
    if num % 2 == 0:
        continue
    print(num)
Output:

Copy code
1
3
5
7
9
Q72. The break statement is used to exit a loop prematurely, skipping over any remaining iterations. It is commonly used in loops to stop the loop execution when a certain condition is met.

Here's an example of using break statement:

bash
Copy code
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]

for num in numbers:
    if num == 5:
        break
    print(num)
Output:

Copy code
1
2
3
4
Q73. The pass statement is a null operation in Python. It is used as a placeholder when no action is required but a statement is needed syntactically.

Here's an example of using pass statement:

arduino
Copy code
if condition:
    pass  # no action required yet
else:
    # do something else
Q74. The range() function in Python generates a sequence of numbers, starting from 0 by default, and increments by 1 by default, and stops before a specified number. It can take one to three arguments: start, stop, and step.

Here's an example of using range() function:

python
Copy code
# generate a sequence of numbers from 0 to 4
for i in range(5):
    print(i)

# generate a sequence of numbers from 2 to 8 with a step of 2
for i in range(2, 9, 2):
    print(i)
Output:

Copy code
0
1
2
3
4
2
4
6
8
Q75. To loop over a dictionary in Python, we can use the items() method of the dictionary. It returns a list of the dictionary's (key, value) tuple pairs, which can be iterated over using a for loop.

Here is an example:

bash
Copy code
my_dict = {'apple': 1, 'banana': 2, 'orange': 3}

# Loop over dictionary
for key, value in my_dict.items():
    print(key, value)
Output:

Copy code
apple 1
banana 2
orange 3

Q76. Write a Python program to find the factorial of a given number.

python
Copy code
num = int(input("Enter a number: "))
factorial = 1

if num < 0:
   print("Factorial does not exist for negative numbers")
elif num == 0:
   print("Factorial of 0 is 1")
else:
   for i in range(1,num + 1):
       factorial = factorial*i
   print("Factorial of",num,"is",factorial)
Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

python
Copy code
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the interest rate: "))
time = float(input("Enter the time period in years: "))

simple_interest = (principal * rate * time) / 100

print("The simple interest is:", simple_interest)
Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

python
Copy code
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the interest rate: "))
time = float(input("Enter the time period in years: "))

compound_interest = principal * (pow((1 + rate / 100), time))

print("The compound interest is:", compound_interest)
Q79. Write a Python program to check if a number is prime or not.

python
Copy code
num = int(input("Enter a number: "))

if num > 1:
   for i in range(2, num):
       if (num % i) == 0:
           print(num, "is not a prime number")
           break
   else:
       print(num, "is a prime number")
else:
   print(num, "is not a prime number")
Q80. Write a Python program to check Armstrong Number.

python
Copy code
num = int(input("Enter a number: "))
sum = 0
temp = num

while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")


Q81. Write a Python program to find the n-th Fibonacci Number.

python
Copy code
def fibonacci(n):
    if n <= 0:
        return "Invalid input"
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)

n = int(input("Enter a positive integer: "))
print(f"The {n}-th Fibonacci number is {fibonacci(n)}")
Q82. Write a Python program to interchange the first and last element in a list.

python
Copy code
def interchange_first_last(lst):
    if len(lst) < 2:
        return lst
    else:
        lst[0], lst[-1] = lst[-1], lst[0]
        return lst

lst = [1, 2, 3, 4, 5]
print(interchange_first_last(lst)) # Output: [5, 2, 3, 4, 1]
Q83. Write a Python program to swap two elements in a list.

python
Copy code
def swap_elements(lst, i, j):
    if i < 0 or i >= len(lst) or j < 0 or j >= len(lst):
        return lst
    else:
        lst[i], lst[j] = lst[j], lst[i]
        return lst

lst = [1, 2, 3, 4, 5]
print(swap_elements(lst, 1, 3)) # Output: [1, 4, 3, 2, 5]
Q84. Write a Python program to find N largest element from a list.

python
Copy code
def n_largest_elements(lst, n):
    lst.sort(reverse=True)
    return lst[:n]

lst = [1, 4, 2, 7, 5, 9]
print(n_largest_elements(lst, 3)) # Output: [9, 7, 5]
Q85. Write a Python program to find cumulative sum of a list.

python
Copy code
def cumulative_sum(lst):
    cum_sum = []
    total = 0
    for i in lst:
        total += i
        cum_sum.append(total)
    return cum_sum

lst = [1, 2, 3, 4, 5]
print(cumulative_sum(lst)) # Output: [1, 3, 6, 10, 15]

Q86. Write a Python program to check if a string is palindrome or not.

A palindrome string is a string that remains the same when its characters are reversed. To check whether a given string is a palindrome or not, we can compare the original string with its reverse. If they are the same, then the string is a palindrome.

Here's the Python code to check if a string is a palindrome or not:

python
Copy code
def is_palindrome(s):
    # Remove spaces and convert to lowercase
    s = s.replace(" ", "").lower()
    
    # Compare original string with its reverse
    if s == s[::-1]:
        return True
    else:
        return False

# Test the function
string1 = "racecar"
print(is_palindrome(string1)) # Output: True

string2 = "Hello, world!"
print(is_palindrome(string2)) # Output: False
Q87. Write a Python program to remove i'th element from a string.

In Python, strings are immutable, which means we cannot modify them directly. However, we can convert a string to a list, modify the list, and then convert it back to a string.

Here's the Python code to remove the i'th element from a string:

python
Copy code
def remove_char(s, i):
    # Convert the string to a list
    chars = list(s)
    
    # Remove the i'th character
    del chars[i]
    
    # Convert the list back to a string
    new_string = "".join(chars)
    return new_string

# Test the function
string = "Python"
index = 2
new_string = remove_char(string, index)
print(new_string) # Output: Pyhon
Q88. Write a Python program to check if a substring is present in a given string.

We can use the in keyword to check if a substring is present in a given string.

Here's the Python code to check if a substring is present in a given string:

python
Copy code
def find_substring(s, substring):
    if substring in s:
        return True
    else:
        return False

# Test the function
string = "Python is a popular programming language"
sub = "pro"
print(find_substring(string, sub)) # Output: True

sub = "java"
print(find_substring(string, sub)) # Output: False
Q89. Write a Python program to find words which are greater than given length k.

We can split a string into a list of words using the split() method, and then iterate through the list to find words that are greater than a given length k.

Here's the Python code to find words which are greater than a given length k:

python
Copy code
def find_long_words(s, k):
    # Split the string into words
    words = s.split()
    
    # Create a list to store long words
    long_words = []
    
    # Iterate through the list and find long words
    for word in words:
        if len(word) > k:
            long_words.append(word)
    
    return long_words

# Test the function
string = "Python is a popular programming language"
k = 5
long_words = find_long_words(string, k)
print(long_words) # Output: ['Python', 'popular', 'programming', 'language']
Q90. Write a Python program to extract unique dictionary values.

We can use a set to extract unique values from a dictionary.

Here's the Python code to extract unique dictionary values:

python
Copy code
def get_unique_values(d):
    # Create a set to store unique values
    unique_values = set()
    
    # Iterate through the dictionary values and

Q91. Write a Python program to merge two dictionaries.

Ans. We can merge two dictionaries using the update() method in Python. Here is an example:

python
Copy code
dict1 = {'a': 10, 'b': 20}
dict2 = {'c': 30, 'd': 40}

dict1.update(dict2)
print(dict1)
Output:

css
Copy code
{'a': 10, 'b': 20, 'c': 30, 'd': 40}
Q92. Write a Python program to convert a list of tuples into dictionary.

Ans. We can convert a list of tuples into a dictionary using dictionary comprehension in Python. Here is an example:

python
Copy code
lst = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
dict = {key:val for key, val in lst}
print(dict)
Output:

arduino
Copy code
{'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Ans. We can create a list of tuples having number and its cube in each tuple using list comprehension in Python. Here is an example:

python
Copy code
lst = [9, 5, 6]
tuple_lst = [(num, num**3) for num in lst]
print(tuple_lst)
Output:

css
Copy code
[(9, 729), (5, 125), (6, 216)]
Q94. Write a Python program to get all combinations of 2 tuples.

Ans. We can get all combinations of 2 tuples using list comprehension and the + operator in Python. Here is an example:

python
Copy code
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
combo_lst = [tup1 + tup2 for tup1 in (test_tuple1, test_tuple2) for tup2 in (test_tuple1, test_tuple2) if tup1 != tup2]
print(combo_lst)
Output:

Copy code
[(7, 2, 7, 7), (7, 2, 7, 8), (7, 2, 2, 7), (7, 2, 2, 8), (7, 8, 7, 7), (7, 8, 7, 2), (7, 8, 8, 7), (7, 8, 8, 2), (7, 7, 7, 2), (7, 7, 8, 7), (7, 2, 7, 7), (7, 2, 7, 8), (7, 8, 7, 7), (7, 8, 7, 2), (2, 7, 7, 7), (2, 7, 2, 7), (8, 7, 7, 7), (8, 7, 8, 7), (7, 7, 2, 7), (7, 7, 7, 8), (7, 2, 2, 7), (7, 2, 2, 8), (7, 7, 8, 7), (7, 7, 8, 2), (7, 8, 8

Q95 We can use the sorted() function along with a lambda function to sort the list of tuples by the second item. Here's the Python code to achieve the desired output:

python
Copy code
tuples_list = [('for', 24), ('Geeks', 8), ('Geeks', 30)]
sorted_list = sorted(tuples_list, key=lambda x: x[1])
print(sorted_list)
Output:

css
Copy code
[('Geeks', 8), ('for', 24), ('Geeks', 30)]
In the above code, tuples_list contains the input list of tuples. The sorted() function sorts the tuples_list based on the second item of each tuple using the key parameter, which takes a lambda function. The lambda function returns the second element of each tuple (x[1]) for sorting purposes. Finally, the sorted list is printed.

Q96 Here's the Python code to print the given pattern:

python
Copy code
for i in range(1, 6):
    print('* ' * i)
Output:

markdown
Copy code
* 
* * 
* * * 
* * * * 
* * * * *


Q97 Here is a Python program to print the pattern:


n = 5
for i in range(1, n+1):
    for j in range(n-i):
        print(" ", end="")
    for k in range(i):
        print("*", end="")
    print()

Output:

    *
   **
  ***
 ****
*****

Q 98 Here's a Python program to print the above pattern:


n = 5

for i in range(1, n+1):
    print(" "*(n-i) + "* "*i)

Output:


    * 
   * * 
  * * * 
 * * * * 

Q99 You can print the given pattern using nested loops. Here's the Python code to print the pattern:


for i in range(1, 6):
    for j in range(1, i + 1):
        print(j, end=" ")
    print()

Output:


1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 

Q100 Here's the Python code to print the given pattern:


n = 5
for i in range(n):
    for j in range(i+1):
        print(chr(i+65), end=" ")
    print()

Output:


A 
B B 
C C C 
D D D D 
E E E E E 



