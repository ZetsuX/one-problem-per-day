# A. I Wanna Be the Guy

Source : [Problem](https://codeforces.com/problemset/problem/469/A)

-   time limit per test 1 second
-   memory limit per test 256 megabytes
-   input standard input
-   output standard output

There is a game called "I Wanna Be the Guy", consisting of n levels. Little X and his friend Little Y are addicted to the game. Each of them wants to pass the whole game.

Little X can pass only p levels of the game. And Little Y can pass only q levels of the game. You are given the indices of levels Little X can pass and the indices of levels Little Y can pass. Will Little X and Little Y pass the whole game, if they cooperate each other?

## Input

The first line contains a single integer n (1 ≤  n ≤ 100).

The next line contains an integer p (0 ≤ p ≤ n) at first, then follows p distinct integers a1, a2, ..., ap (1 ≤ ai ≤ n). These integers denote the indices of levels Little X can pass. The next line contains the levels Little Y can pass in the same format. It's assumed that levels are numbered from 1 to n.

## Output

If they can pass all the levels, print "I become the guy.". If it's impossible, print "Oh, my keyboard!" (without the quotes).

## Examples

### Sample Input 1

    4
    3 1 2 3
    2 2 4

### Sample Output 1

    I become the guy.

### Sample Input 2

    4
    3 1 2 3
    2 2 3

### Sample Output 2

    Oh, my keyboard!

## Note

In the first sample, Little X can pass levels [1 2 3], and Little Y can pass level [2 4], so they can pass all the levels both.

In the second sample, no one can pass level 4.
