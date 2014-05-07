# So You Think You Can Count

So You Think You Can Count is a book that aims to teach that counting hides with in it 
enormous beauty. It teaches counting by a problem oriented approach. 

To show how counting can be tricky consider the following two problems:

1. In how many ways can the numbers 1,...,n be placed in the cells of an n×n
grid, with no restriction on how many times each is used? Since each of the
n^2 cells can have its entry chosen independently from a set of n possibilities,
the answer is (n^n)^2.

2. In how many ways can the arrangement be made if each number must occur
once in each row? Once we notice that each row must be a permutation of
the numbers 1,...,n, and that the permutations can be chosen independently,
we see that the answer is (n!)^n (as there are n! permutations of the numbers
1,...,n).

3. In how many ways can the arrangement be made if each number must occur 
once in each row and once in each column? For this problem, there is
no formula for the answer. Such an arrangement is called a Latin square.
The number of Latin squares with n up to 11 has been found by brute-force
calculation. For larger values, we don’t even have good estimates: the best
known upper and lower bounds differ by a factor which is exponentially
large in terms of the number of cells.

Not all problems are as hard as this. In this book you will learn how to count
the number of permutations which move every symbol, strings of zeros and ones
containing no occurrence of a fixed substring, invertible matrices of given size
over a finite field, expressions for a given positive integer as a sum of positive
integers (the answers are different depending on whether we care about the order
of the summands or not), trees and graphs on a given set of vertices, orbits of the
general linear group on tuples of vectors, zero-one matrices of unspecified size
with a given number of ones, any many more.


# References

TBD

# License
Copyright (c) 2013-2014 Srinivas Kowtal. Licensed under [the MIT license](http://opensource.org/licenses/MIT).