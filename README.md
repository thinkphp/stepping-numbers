Stepping Numbers
----------------

A number is called stepping number if all adjacent digits have an absolute difference of 1, e.g. '321' is a Stepping Number 
while 421 is not. Given two integers n and m, find the count of all the stepping numbers in range [n, m].

Input : n = 0, m = 21
Output : 13
Stepping no's are 0 1 2 3 4 5 6 7 8 9 10 12 21

Input : n = 10, m = 15
Output : 2
Stepping no's are 10, 12

Input:
The first line of the input contains an integer T, denoting the number of test cases. Then T test case follows. 
The only line of each test case contains two space separated integers denoting the values of n and m respectively.


Output:
For each test case in a new line print an integer denoting the number of stepping numbers in the range between n and m.

Constraints:
1<=T<=102
0<=N,M<=10^6

Example:
Input:
3
0 21
10 15
0 1
Output:
13
2
2