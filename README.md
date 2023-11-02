# Fibonacci
The nth Fibonacci number can be efficiently calculated using dynamic programming by utilizing the method defined in the "Fibonacci" class defined in this Java code. A synopsis of the code is provided below:
Dynamic programming is used to determine the nth Fibonacci number via the "Fibonacci" class's static function "fib". The numerical array "dp" of size "n + 1" is initialized to hold Fibonacci numbers, with "n" representing the input value that needs to be found.
Given that these are the first two Fibonacci numbers, it sets the base cases for Fibonacci, "dp[0]" to 0 and "dp[1]" to 1. Adding the preceding two numbers to each Fibonacci number, the code iterates
from "i = 2" to "n," calculating and storing each number in the "dp" array.

#Coin Change
To address the Coin Change issue, the code defines a class named "coinchange". It offers a way to "print" the contents of a 2D array, which is useful for visualizing dynamic programming tables. The "coinchange" method determines how many different ways there are to use
the specified coin denominations to generate a target total. It use a 2D array called "dp" to hold intermediate results, where "dp[i][j]" denotes methods for generating sum "j" from the first "i" coin denominations.In order to determine how many methods there are to make the goal sum, the
code initializes base cases, iterates through coins and total, and fills the "dp" table. After printing the table for visualization, it gives back the outcome.The code finds the number in the main method to show how to use the
"coinchange" function.

#Knapsack
In order to address the 0/1 Knapsack problem, the code constructs a class named "knapsack01". It offers a way to "print" a 2D array's contents, which is commonly used to visualize dynamic programming tables.
With respect to item values, weights, and a maximum capacity, the "Knap" approach determines the highest value that may be obtained in the 0/1 Knapsack issue. In order to store interim results, it first initializes a 2D array called "dp,"
where "dp[i][j]" denotes the maximum value with the first "i" elements and a knapsack capacity of "j." The code considers whether to include or exclude each item in the knapsack depending on weight limitations,
setting base cases to 0 and filling the "dp" table accordingly. The variable "dp[n][W]," where "n" is the number of elements, stores the highest value that may be achieved.

#Matrix Multiplication
This Java code creates a class called "MatrixMultiplication" and uses a recursive method to determine the minimal cost of matrix chain multiplication. The code is described as follows in brief:
A static method called "mcm" in the "MatrixMultiplication" class iteratively determines the least amount of money needed to multiply a chain of matrices. "I" and "j" are indices that specify the current range of matrices to be multiplied,
and the procedure accepts an array "arr" that represents the dimensions of matrices. In order to divide the matrix chain into smaller issues, the "mcm" algorithm loops over various partition points ("k"). Along with multiplying the resulting
submatrices, it also computes the cost of multiplying the matrices on the left and right sides of the split. Among these partitions, it determines which has the lowest cost.
As the best method of parenthesizing the matrices for the lowest total cost, the code gives the smallest cost of matrix chain multiplication.The code presents an array representing matrix dimensions in the main method,
where it finds the minimal cost of multiplying the matrices. This illustrates how to use the "mcm" function. For bigger matrix chains, this code may not be the most effective method because it takes a recursive approach.
