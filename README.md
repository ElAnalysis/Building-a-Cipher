# Building-a-Cipher
# **Learning string manipulation by building a cipher**
## **Python**

<br>

### **Functions**

<br>

**print()** - display

**len()** - count the characters

**type** - returns the data type of a variable 

<br>
<br>

### **Variable Naming rules**

<br>

**Key aspects of variable naming in Python:**

- Some words are reserved keywords (eg. for, while, True) They have special meaning in Python, so you cannot use them for variable names.
- Variable names cannot start with a number, and they can only contain alpha-numeric characters or underscores.
- Variable names are case sensitive(ie. My_var is different from my_var)
- It is a common convention to write variable names using snake_case, where each space is replaced by an underscore character and the words are written in lowercase letters.
  

### **Methods**
(Similar to a function, but it belongs to an object)

<br>

example:

sentence = 'My brain hurts!'

sentence.find(‘r’)

<br>

Above, the .find() method is called on sentence (the string to search in), and 'r' (the character to locate) is passed as the argument. The sentence.find('r') call will return 4, which is the index of the first occurrence of 'r' in sentence.

<br>
<br>

**.find()**

**.lower()** - Can transform a string into a lowercase equivalent.

<br>
<br>

Example of combining **.find()** and **.lower()**

<br>

text = 'Hello World'

shift = 3

alphabet = 'abcdefghijklmnopqrstuvwxyz'

index = alphabet.find(text[0].lower())

print(index)

<br>
<br>

With **.lower** being part of the index variable it made all the string variable text into all lowercase which allowed the **.find** method to locate the sting letter ‘h’ under index number 7

<br>
<br>

A loop allows you to systematically go through a sequence of elements and execute actions on each one.

In this case, you'll employ a for loop. 

Here's how you can iterate over text:

<br>

Example Code

<br>

for i in text:

<br>
<br>

**for** is the keyword denoting the loop type. **i** is a variable that sequentially takes the value of the elements in text. The statement ends with a colon, :



The code to execute at each iteration — placed after the : — constitutes the body of the loop. This code must be indented. In Python, it is recommended to use 4 spaces per indentation level. This indented level is a code block.

<br>

Example Code

<br>

for i in text:
    print(i)

<br>
<br>

Python relies on indentation to indicate blocks of code. A colon at the end of a line is a signal that a new indented block of code will follow.

So, when no indented block is found after the final colon, the code execution stops and an IndentationError is thrown. This code will not show the output and instead raise an IndentationError:

<br>

Example Code

<br>

for i in text:
print(i)

<br>
<br>

You can obtain the same effect of a = a + b by using the addition assignment operator:

Example Code

<br>

a **+=** b

<br>
<br>

The addition assignment operator enables you to add a value to a variable and then assign the result to that variable.

Comparison operators allow you to compare two objects based on their values. You can use a comparison operator by placing it between the objects you want to compare. They return a Boolean value — namely True or False — depending on the truthfulness of the expression.

<br>
<br>

### **Python has the following comparison operators:**
**Operator	Meaning**
<br>
* **==**	Equal
* **!=**	Not equal
* **>**	Greater than
* **<**	Less than
* **>=**	Greater than or equal to
* **<=**	Less than or equal to
