# Lesson 1: Hello World!

Programming languages allow for programmers to give instructions to a computer. The specificity of these instructions is dependent on how much control the programming language allows the programmer to work directly with the manipulation of bits on a computer.  

High-level languages like Python and Javascript offer programmers little control over a computer's memory and bits, but offer a lot of features that can save programmers from headaches when writing code.  

Lower-level languages like C/C++, Rust, and Assembly offer programmers greater amounts of control over a computer's memory, but lack the convenient features of higher-level languages. However, due to a lack of these features, lower-level programming languages have the potential to run faster and be more efficient than their higher-level counterparts, and thus are used to write game engines, drivers, and operating systems.  

Let's write a simple program that outputs a message to the screen. To output a message in pseudocode, the `DISPLAY` command is used. For example, if I were to output the message "Hello World!", I would write:  

`DISPLAY("Hello World!")`  

> **Side Note** Most programming languages utilize a `print` command or a variation of it to output a message to the screen. This is due to the fact that the majority of the existing programming languages can trace most of their roots to the programming language C, which was created by Dennis Ritchie in 1972.
>> You'll see side notes throughout these lessons. They're not essential concepts for AP Computer Science Principles, but they're nice to know things that can provide a greater understanding of computer science.  

The parenthesis let the computer know what to output for the `DISPLAY` command. The quotes inside the parenthesis let the computer know that the text within them is a *string* (a series of letters and symbols à la words).

> As stated in Lesson 0, computers understand data through binary bits, so how do programming languages that use regular words (such as `DISPLAY`) get understood by a computer? Programming languages have *compilers* or *interpreters* that convert the code in programming languages into machine code (1s and 0s) that computers can understand. A compiler converts the entirety of the code into machine code, and then runs the newly created machine code, while an interpreter converts and runs one line of code at a time. Some languages are compiled while some are interpreted.  

### Problems  

(use https://pseudocode.run to run these practice problems)

1. Change the text in the `DISPLAY("Hello World!")` program we wrote earlier to output a message of your choice.
2. Write a program that displays the lyrics to "Twinkle Twinkle Little Star"
3. **Challenge:** Try figuring out how to output numbers using the `DISPLAY` command (hint: Don't use quotation marks).
