# Lesson 2: Variables  

Programs would be quite boring if all values were known and constant. At times, programmers may need to utilize containers to store certain values. These containers are called *variables*.  

Variables are widely used in computer programs. For example, a variable would be utilized to store somebody's username and password on a website.  

Variables can store a variety of things, such as numbers, `true`/`false` values, unicode characters, and strings. 

> **Side Note:** You'll remember in Lesson 0 that computers mainly use binary numbers to store and process data. Unicode creates a standardized way

To create a variable in pseudocode, the `name ← value` syntax is used. For example, if you were to create a variable called `a` and assign the value 5 to it, the code would be written as:  

`a ← 5`

In this case, the value of 5 is being stored in the variable `a`.  

In pseudocode, the `INPUT` command allows for the receiving of user input. The `INPUT` command receives user input and allows for it to be stored in a variable, like so:  

`x ← INPUT()`

The above code stores user input in the variable `x`. Note the usage of parentheses.

You can print variables using the `DISPLAY` function as well. The code:  

`a ← 5`  

`DISPLAY(a)`  

Would output a value of 5. 

There are also arithmetic operators present that you can use to manipulate the value of numbers. The `+` operator adds two numbers, the `-` operator subtracts two numbers, the `*` operator multiplies two numbers, the `/` operator divides two numbers, the `^` operator raises one number to the power of another, and the `%` operator performs the modulo operation, i.e. gives the remainder of two numbers after division.  

`a ← 3 + 2 //Stores the sum of 3 and 2 into a, which is 5`  

`b ← 5 - 4 //Stores the difference of 5 and 4 into b, which is 1`  

`c ← 3 * 8 //Stores the product of 3 and 8 into c, which is 24`  

`d ← 4 / 2 //Stores the quotient between 4 and 2 into d, which is 2`

`e ← 3 ^ 2 //Stores 3 raised to the second power into 3, which is 9`  

`f ← 4 % 3 //Stores the remainder after 4 is divided by 3 into f, which is 1`

> **Side Note:** The `//` indicates a *comment* in code. Text following the `//` in the same line is ignored by the compiler, and is only used to annotate and explain code.  

### Problems:
1. Write a program that stores a number in a variable and prints that variable
2. Write a program that asks for a persons first and last name and prints it.
3. Write a program that prints the modulo of two inputted numbers.
4. **Challenge:** Write a program takes in two base sides of a right triangle and prints the length of the hypotenuse.
