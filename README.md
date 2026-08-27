# ECE-2112-Advanced-Computer-Programming-and-Algorithms-Programming-Assignment-
My Programming Assignment #1 for my ECE 2112: Advanced Computer Programming and Algorithms, which includes the uses and applications of the lessons attained from Module #!

1. Word Rotation Problem

Goal: Create a function named rotate_word that accepts a string, and create code that would allow you to move the first element of the given word to the end of the given word, while preserving the original capitalization of the given word. 

Implementation:

Initially, the way I started thinking about how to solve the problem was, first, how to receive the given word, which I had two thoughts. 

A. Create a function that could be used later on, and print the given word later

B. Create a way for the user to input the given word, and create a function that pursues the goal 

Solution: Option A

Coding: The initial step in the code was to define a function named rotate_word that takes its corresponding parameters, allowing me to use it later when printing examples. Aftwards, I created a line of code that would return the given word but in parts via "slicing" and "indexing". Initially, the word was sliced at index[1] or the second element, word[1:] which is what allowed for the first letter to be removed, while it was indexed at the end by adding word[0], which was combined by the concept of Concatenation, which is the combining of strings via the syntax, "+", which solved the last problem of removing the space. 

