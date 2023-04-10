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
> 1. Accessing nth element of an array

> 2. Push and pop a stack

> 3. Add and remove a queue elememt

> 4. Accessing an element of Hash-Table

##### Linear Time O(n)
An algorithm will run in linear time if the execution time of the algorithm is directly proportional to the input size. That is, as the input size increases, execution time increases. Examples of linear time algorithms:
> 1. Array operations like search elememt, find minimum and maximum element.

> 2. LinkedList operations like traversal, find minimum and maximum element.

##### Logarithmic Time O(log n)
An algorithm will run in logarithmic time if the execution time of the algorithm is proportional to the logarithm of the input size. That is, a significant portion of the input is pruned or cut off (divided in half/half portion) without traversing it. Examples of logarithmic time algorithm:
> Binary search algorithm

##### N-LogN Time O(n log n)
An algorithm will run in n logn time if the execution time of the algorithm is proportional to the product of the input size and logarithm of the input size. That is, each time the input is divided into half and each portion is processed independently. Examples of nlogn time algorithm:
> Merge, quick and heap sorting algorithms

##### Quadratic Time O(n^2)
An algorithm will run in quadratic time if the execution time of the algorithm is proportional to the square of the input size. Here each element is compared with all other elements. Examples of quadratic time algorithm:
> Bubble, selection and insertion sorting algorithms

##### Exponential Time O(2^n)
Here all possible subsets of elements of input data are generated.

##### Factorial Time O(n!)
Here all possible permutations of elements of input data are generated.

Now let's see how we can derive the runtime function of an algorithm:
> * Constants: each statement takes a constant time to run. Time complexity is O(1)
> * Loops: running time of a loop is a product of running time of the statement inside a loop and number of iterations in the loop. Time complexity is O(n)
> * Nested Loop: running time of a nested loop is a product of running time of the statements inside loop multiplied by a product of the size of all the loops. Time complexity is O(n^c), where c is the number of loops. For example, two loops will be O(n^2)
> * Consecutive Statements: Add running times of all the consecutive statements.
> * If-Else Statements: Just add the larger block of if or else and ignore the other block.
> * Logarithmic Statement: If in each iteration the input size is decreased by a constant factor, then the time complexity is O(log n)
