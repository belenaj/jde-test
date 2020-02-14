# Programming exercise

## Choose a programming language
You can choose any program language for completing these exercises.

## Introduction
A collection is a data structure which contains different items. Each item is located in a specific position inside the collection. Specific item order inside a collection forms a permutation. It is possible to get different permutations with the same set of items. A permutation can contain all elements or a subset of them.

Example 1: Given set {A, B, C}, all permutations with all elements are:

|Permutation ID | Position [0] | Position [1] | Position [2] |
|:-------------:|:------------:|:------------:|:------------:|
|P<sub>1-1</sub>|A             |B             |C             |
|P<sub>1-2</sub>|A             |C             |B             |
|P<sub>1-3</sub>|B             |A             |C             |
|P<sub>1-4</sub>|B             |C             |A             |
|P<sub>1-5</sub>|C             |A             |B             |
|P<sub>1-6</sub>|C             |B             |A             |

Example 2: Given set {A, B, C}, all permutations with a subset of 2 elements are:

|Permutation ID | Position [0] | Position [1] |
|:-------------:|:------------:|:------------:|
|P<sub>2-1</sub>|A             |B             |
|P<sub>2-2</sub>|A             |C             |
|P<sub>2-3</sub>|B             |A             |
|P<sub>2-4</sub>|B             |C             |
|P<sub>2-5</sub>|C             |A             |
|P<sub>2-6</sub>|C             |B             |

In this test, <u>all permutations expected included all elements</u> (Example 1)

## Exercise 1
Given a collection of Integer numbers:
```
[104, 598, 625, 158, 598]
```
- Develop a function which calculates all permutations among array elements.
- Develop a function which calculates all permutations among distinct array elements.
- Develop a unit test case (one or more) for testing your functions.
- What is the cost of your algorithm solution?

## Exercise 2
Given a collection of Integer numbers (Integer numbers greater or equal to 0 and less than 1000 without duplicated values):
```
[0, 1, 2, ..., 998, 999]
```
- Develop a function which generates the collection with this data set.
- Develop a function which calculates all permutations among array elements excluding the ones with numbers multiple of 5 in consecutive positions.
  - Example of exclusion
```
# This permutation must be excluded because there are two numbers multiple of 5 consecutives (5, 225)
[4, 234, 5, 225, ...]
```
- Develop a unit test case (one or more) for testing your functions.
- How much permutations there are?
- What is the cost of your algorithm solution?

## Work to deliver

We like clean, clear and readable code. Also we like that the code we execute is efficient.

When work is completed it's necessary to send 3 text files:
- File 1: A file which contains source code for exercise 1. Name of this file must be: exercise-1.txt or exercise-1.zip (if you have created multiple files)
- File 2: A file which contains source code for exercise 2. Name of this file must be: exercise-2.txt or exercise-2.zip (if you have created multiple files)
- File 3: A file which contains notes/explanations. Name of this file must be: notes.txt. This file can be done using markdown, but name must be the defined before. At least must be:
    - How to compile your source code.
    - Answers of questions presents in different exercesises.
    - Optional: any other explanation relevant about solutions.
