# A. Three Pairwise Maximums

Source : [Problem](https://codeforces.com/problemset/problem/1385/A)

-   time limit per test 1 second
-   memory limit per test 256 megabytes
-   input standard input
-   output standard output

You are given three positive (i.e. strictly greater than zero) integers x, y and z.

Your task is to find positive integers a, b and c such that x=max(a,b), y=max(a,c) and z=max(b,c), or determine that it is impossible to find such a, b and c.

You have to answer t independent test cases. Print required a, b and c in any (arbitrary) order.

## Input

The first line of the input contains one integer t (1 ≤ t ≤ 2⋅10^4) — the number of test cases. Then t test cases follow.

The only line of the test case contains three integers x, y, and z (1 ≤ x, y, z ≤ 10^9).

## Output

For each test case, print the answer:

-   "NO" in the only line of the output if a solution doesn't exist;
-   or "YES" in the first line and any valid triple of positive integers a, b and c (1 ≤ a, b, c ≤ 10^9) in the second line. You can print a, b and c in any order.

## Example

### Sample Input 1

    5
    3 2 3
    100 100 100
    50 49 49
    10 30 20
    1 1000000000 1000000000

### Sample Input 2

    YES
    3 2 1
    YES
    100 100 100
    NO
    NO
    YES
    1 1 1000000000
