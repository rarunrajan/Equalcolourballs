
You are given a sequence of balls in 4 colors: red, green, yellow and blue. The sequence is full of colors if and only if all of the following conditions are true:

    There are as many red balls as green balls.
    There are as many yellow balls as blue balls.
    Difference between the number of red balls and green balls in every prefix of the sequence is at most 1.
    Difference between the number of yellow balls and blue balls in every prefix of the sequence is at most 1.

Your task is to write a program, which for a given sequence prints True if it is full of colors, otherwise it prints False.

Input
In the first line there is one number
denoting the number of tests cases.
lines follow. In each of them there is a sequence of letters denoting the input sequence ( - red, - green, - yellow, -blue).

Output
For each test case, print True if this is a sequence full of colors, otherwise print False.

Constraints

Sequence will only consists of letters .
Sum of length of all sequences will not exceed

.

Notes
A prefix of a string
is a string , where

.

Sample Input

4
RGGR
RYBG
RYRB
YGYGRBRB

Sample Output

True
True
False
False

Explanation
In the first two test cases, all four conditions are satisfied.
In the third test case, condition #1 fails as there are more red balls than green balls and condition #3 also fails for prefix "RYR" as the difference between the number of red and green balls is more than 1. In the fourth test, for a prefix "YGYG" condition 4th fails.
