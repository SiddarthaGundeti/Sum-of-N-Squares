# Sum-of-N-Squares

Question Explanation:

The program aims to calculate the sum of the squares of the first N natural numbers. The sum of squares refers to the sum of the square of each individual number from 1 to N.

Logical Approach:

Read Input:
Read the integer N which specifies how many numbers to include in the calculation.

Initialize Variables:
Initialize a counter variable to keep track of the count of numbers processed.
Initialize sum_of_squares_of_N to 0 to store the cumulative sum of squares.

Calculate Sum of Squares:
Use a while loop to iterate through the numbers from 1 to N.
In each iteration:
Increment counter by 1.
Calculate the square of the counter and add it to sum_of_squares_of_N.

Output:
After the loop, print sum_of_squares_of_N which contains the sum of squares of numbers from 1 to N.

Example for Clarity:

If the input N is 4:

The first 4 natural numbers are 1, 2, 3, and 4.

Their squares are 1² = 1, 2² = 4, 3² = 9, and 4² = 16.

The sum of these squares is 1 + 4 + 9 + 16 = 30.

The output will be: 30
