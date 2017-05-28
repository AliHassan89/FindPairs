In an array of integers, we consider a pair of elements, (a, b), to be a valid 
pair if a = b. Two valid pairs, (a, b) and (c, d), are considered to be the same 
pair if any of the following two conditions are true:
a ? c and b ? d
a ? d and b ? c
For example, the array [1, 1, 1, 2] has a total of two valid pairs: (1, 1) and 
(1, 2). Note that all instances of the pair (1, 1) count as a single valid pair.
 
Complete the countPairs function in the editor below. It has two parameters:
An array of n integers, numbers.
An integer, k.
The function must return an integer denoting the count of valid (a, b) pairs in 
the numbers array that have a difference of k (i.e., where a + k = b).
 
Input Format
Locked stub code in the editor reads the following input from stdin and passes 
it to the function: The first line contains an integer, n, denoting the number 
of elements in the numbers array. Each line i of the n subsequent lines 
(where 0 = i < n) contains an integer describing numbersi.
The last line contains an integer, k.
 
Constraints
2 = n = 2 × 105
0 = numbersi = 109, where 0 = i < n
0 = k = 109
 
Output Format
The function must return an integer denoting the number of valid pairs in the 
numbers array that have a difference of k. This is printed to stdout by locked 
stub code in the editor.