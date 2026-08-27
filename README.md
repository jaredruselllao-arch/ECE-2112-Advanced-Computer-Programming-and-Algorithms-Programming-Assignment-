# ECE-2112-Advanced-Computer-Programming-and-Algorithms-Programming-Assignment-
My Programming Assignment #1 for my ECE 2112: Advanced Computer Programming and Algorithms, which includes the uses and applications of the lessons attained from Module #1

1. Word Rotation Problem

   Goal: Create a function named rotate_word that accepts a string, and create code that would allow you to move the first element of the given word to the end of the given word, while preserving the original capitalization of the given word. 

Implementation:

Initially, I started thinking about how to solve the problem by first considering how to receive the given word, which I had two thoughts on. 

A. Create a function that could be used later on, and print the given word later

B. Create a way for the user to input the given word, and create a function that pursues the goal 

Solution: Option A

Coding: The initial step in the code was to define a function named rotate_word that takes its corresponding parameters, allowing me to use it later when printing examples. Aftwards, I created a line of code that would return the given word but in parts via "slicing" and "indexing". Initially, the word was sliced at index[1], or the second element, word[1:], which allowed the first letter to be removed. In contrast, it was indexed at the end by adding word[0], combined via concatenation (the combining of strings via the syntax "+"), which solved the last problem of removing the space. 

2. USERNAME BUILDER PROBLEM

   Goal: Create a function named make_username() that could hold 2 parameters, and do the following: convert all letters to lowercase, remove all spaces from the first name, remove all spaces from the last name, and join the first and last name via a period.

   Implementation:

   I started the code by creating the required function, make_username(), with parameters first_name and last_name, allowing me to use multiple parameters in the function. Afterward, I handled each required step one by one. Firstly, to convert all letters to lowercase, I had to attach .lowercase() to first_name and last_name, then add .replace(" ", ""), which replaces spaces in the given name with no spaces, removing them. This was applied to both the first_name and last_name. Moreover, this was all concatenation, which allowed me to combine both names without spaces and add a period in the middle to create the sense of replacing the space with a period. This was all used in the return section of the function, which allowed me to use it later on the printed samples. 

3. BOOKEND SWAP PROBLEM

   Goal: Create the function named swap_bookends that accepts at least two parameters. By doing so, create the 3 parameters: first, middle, and last, and have the first and last switch positions while the middle stays exactly the same.

   Implementation: Firstly, I started the code by defining the function swap_bookends with the parameter item, which initially seemed like a mistake because it only had one parameter, but it was used in a unique way. The parameter item was then "unpacked" into first, middle, and last, allowing 3 arguments in the function, as a list. Lastly, using indexing, from the perspective of a list, we had the function return the last option, then the middle ones, then the first one, in that order. Moreover, this was only possible due to the syntax, *middle, which also was what allowed everything aside from the start and end be kept together. 
