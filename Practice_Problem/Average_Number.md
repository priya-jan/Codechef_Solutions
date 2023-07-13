Chef had a sequence of positive integers with length N+KN+K. He managed to calculate the arithmetic average of all elements of this sequence (let's denote it by VV), but then, his little brother deleted KK elements from it. All deleted elements had the same value.

Chef still knows the remaining NN elements — a sequence A1,A2,…,ANA1​,A2​,…,AN​. Help him with restoring the original sequence by finding the value of the deleted elements or deciding that there is some mistake and the described scenario is impossible.

Note that the if it is possible for the deleted elements to have the same value, then it can be proven that it is unique. Also note that this value must be a positive integer.
Input

    The first line of the input contains a single integer TT denoting the number of test cases. The description of TT test cases follows.
    The first line of each test case contains three space-separated integers NN, KK and VV.
    The second line contains NN space-separated integers A1,A2,…,ANA1​,A2​,…,AN​.

Output

For each test case, print a single line containing one integer — the value of the deleted elements, or −1 if there is a mistake.
Constraints

    1≤T≤1001≤T≤100
    1≤N,K≤1001≤N,K≤100
    1≤V≤1051≤V≤105
    1≤Ai≤1051≤Ai​≤105 for each valid ii

Subtasks

Subtask #1 (100 points): original constraints
Sample 1:
Input

3
3 3 4
2 7 3
3 1 4
7 6 5
3 3 4
2 8 3

Output

4
-1
-1