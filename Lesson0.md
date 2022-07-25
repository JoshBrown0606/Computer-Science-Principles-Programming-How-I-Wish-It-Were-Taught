# Lesson 0: The Basics of All Computers - Binary

> **Disclaimer:** This lesson series is meant to teach programming in AP Computer Science Principles in the way I wish it were taught.  
> If I deem a topic in AP Computer Science Principles unnessecary to teach basic programming principles, it will be omitted from these lessons.
> Additionally, certain topics will appear that are not covered as a part of AP Computer Science Principles, but I feel like they will be helpful to learn.
> For all of these reasons, these lessons should be used as a *supplement* to the actual AP Computer Science Principles course, and not as a replacement.  

Computer Science is all about understanding computers and how to manipulate them. At its simplest definition, a computer is something that can read data, manipulate it based on a series of instructions, and then output a result.  

However, a wide range of things can be represented by data. Words, numbers, and pictures are complex things for a device to process. Computers don't have human consciousness or logic to understand this data, so data must be simplified.  

The simplest piece of data for a computer scientist is whether something is true or false. 1 or 0. Yes or no. On or off. Anything with two possible states is very simple to represent for an electronic device.  

Any *boolean* data (something with two possible outcomes) can be represented on a single wire carrying electrical current. A wire with electricity passing through it can either be on or off. "On" wires are represented as 1, and "off" wires are represented as 0.  

Data can be displayed using a single 1 or 0 is called a "bit". However, if a computer has only 1 wire, not much data can be shown or processed. Generally, computers have multiple wires representing *binary* (1s and 0s) data at a time. When you hear somebody call a computer "32 bit" or "64 bit", they're talking about the number of bits of data (i.e. the number of wires) that is used each time the computer receives instructions.  

The next simplest form of data to represent is numbers. However, numbers in a computer behave a little differently than the numbers we use for math. For example, "10" represents ten normally, but it means two in binary.

This is because computers use a "base 2" counting system, while we use a "base 10" counting system in math. In a base 10 counting system, 1 digit can represent the numbers 1 through 9, but the number 10 requires another digit to be used (with a "1" in the tens place and a "0" in the ones place).  

In binary, there is no ones, tens, hundreds, thousands, or any other place that is a power of 10. Instead, there are places for digits for the powers of two: ones place, twos place, fours place, eights place, etc.  

So, the number 1 in binary would be "1", 2 would be "10", 3 would be "11", 4 would be "100", and so on. Each digit in binary can only have a 0 or a 1 in it, so the next digit should be used to represent the next number.  

Once numbers can be represented using binary data, displaying colors and letters can all be achieved using a codified system. 

Different quantities of bits have different names, much like any other form of measurement. A "byte" is 8 bits, a kilobyte is 1024 bytes (yes, that does say "1024"), a megabyte is 1024 kilobytes, a gigabyte is 1024 megabytes, and so on.  

But, giving instructions to a computer in the form of binary data can be hard. While computers can understand binary perfectly fine, it's hard for a person to read a slew of 1s and 0s. Thus, these instructions are *abstracted* and turned into *assembly language*.  

Assembly language is very *low level*; it involves people providing instructions to directly manipulate data is on a computer's processor. Processors are not standardized between computers, meaning that different computers may require different assembly languages to be used.  

Standardized forms of instruction for computers are presented in the form of programming languages such as C, Javascript, Python, Rust, and more.  

Programming languages taught in AP Computer Science Principles vary based on the instructor. Javascript and Python and the most commonly taught languages, but I personally see Java as a good first programming language. However, the questions on the AP Computer Science Principles use a form of *pseudocode* (a fake programming language used to prototype projects or show examples), and I will be teaching using this pseudocode to keep my lessons as language nonspecific as possible.  

If you wish to learn Java, the w3schools course on Java is an excellent resource to learn the language.

> **For the initiated:** I personally believe that Java is a great first language, albeit the fact that it contains considerable amounts of boilerplate (repetitive code), as it makes object-oriented thinking not only a convenience, but a necessity. Java also opens to room for discussion on more advanced programming concepts such as how memory for classes and primitives are dealt with without having to make the learner understand the nitty-gritty details of coding with pointers that lower-level languages require.  

At the end of each lesson there will be a series of practice questions. For practice questions that require programming in AP Pseudocode, an online interpreter can be found at https://pseudocode.run  

### Problems:  

1. Convert the number 20 from decimal (base-10) into binary (base-2)
2. Convert the number 11001 from binary into decimal
3. Remember that a byte is 8 bits. What is the largest number a byte can represent (in binary)?
4. Convert the answer to question 3 into decimal.
5. **Challenge:** Convert the result of the expression 1011101 - 0100101 from binary into decimal.
