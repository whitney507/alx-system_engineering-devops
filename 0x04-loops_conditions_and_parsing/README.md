Shell Scripting Guide
This guide provides an overview of several important topics in shell scripting:

How to create SSH keys
Advantages of using #!/usr/bin/env bash over #!/bin/bash
Using while, until, and for loops
Using if, else, elif, and case condition statements
Using the cut command
Files and other comparison operators
How to create SSH keys
To create SSH keys, follow these steps:

Open a terminal or command prompt.
Use the ssh-keygen command with the appropriate options. For example, ssh-keygen -t rsa will generate an RSA key pair.
Enter a file path to save the keys or accept the default path.
Optionally, provide a passphrase for added security.
The public and private key files will be generated.
Advantages of using #!/usr/bin/env bash over #!/bin/bash
Using #!/usr/bin/env bash has several advantages:

It allows the script to be executed even if the bash interpreter is located in a different directory.
It provides better portability and flexibility in different environments.
It avoids hardcoding the specific path to the bash interpreter.
Using while, until, and for loops
While loop
The while loop executes a block of code repeatedly as long as a condition is true. Here's an example:

while condition
do
    # Code to be executed
done
Until loop
The until loop executes a block of code until a condition becomes true. Here's an example:

until condition
do
    # Code to be executed
done
For loop
The for loop iterates over a list of values and executes a block of code for each value. Here's an example:

for variable in list
do
    # Code to be executed
done
Using if, else, elif, and case condition statements
If statement
The if statement allows for conditional execution of code. Here's the syntax:

if condition
then
    # Code to be executed if the condition is true
fi
Else statement
The else statement provides an alternative code block to execute when the condition is false. Here's the syntax:

if condition
then
    # Code to be executed if the condition is true
else
    # Code to be executed if the condition is false
fi
Elif statement
The elif statement allows for handling multiple conditions. Here's the syntax:

if condition1
then
    # Code to be executed if condition1 is true
elif condition2
then
    # Code to be executed if condition1 is false and condition2 is true
else
    # Code to be executed if both condition1 and condition2 are false
fi
Case statement
The case statement matches a variable or expression against a set of patterns. Here's the syntax:

case expression in
    pattern1)
        # Code to be executed if expression matches pattern1
        ;;
    pattern2)
        # Code to be
