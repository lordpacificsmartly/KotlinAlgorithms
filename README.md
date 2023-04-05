# Kotlin Algorithms

This is a repository of Data Structures and Algorithms in Kotlin

* Introduction - Algorithm Analysis

First let's look at Algorithm Analysis, this is to help us understand the underlying principles of how algorithms work.
An algorithm is simply a set of steps to accomplish a task. The most important properties of an algorithm are:

> Correctness: it should be able to process all given inputs and provide correct output.

> Efficiency: it should be measured in two parameters called Time complexity and Space complexity.
Time complexity - denoted T(n) - measures are quick result is provided by an algorithm, i.e time required versus the the input size.
Space complexity - denoted S(n) - measures memory consumed to give desired results, i.e memory used versus the input size.

Asymptotic analysis is used to compare the efficiency of an algorithm independent of any data set or programming language.

Big - O Notation is simply a notation to describe the behaviour of algorithms. It describes the worst case scenario and provide an upper bound for the algorithm. A list of commonly used Big-O notation in increasing order:


| Name   |      Notation      |
|----------|:-------------:   |
| Constant |  O(1) | :-------------:
| Logarithmic |    O(log n) | :-------------: 
| Linear | O(n) |
| N-Log N | O(n log n)        |
| Quadratic | O(n^2) |
| Polynomial | O(n^c) c is a constant & c > 1 | 
| Exponential | O(c^m) c is a constant & c > 1 |
| Factorial or N-power-N | O(n!) or O(n^n) |

##### Constant Time O(1)
An algorithm will run in constant time if the output is produced in constant time regardless of the input size.
Examples of constant time algorithms:
> 1 Accessing nth element of an array
> 2 Push and pop a stack
> 3 Add and remove a queue elememt
> 4 Accessing an element of Hash-Table
