# H. Palindrome   
   
## Problem Statement   
   
Time: ```limit per test 3 seconds```   
Memory: ```limit per test 256 megabytes```   
Input: ```standard input```   
Output: ```standard output```   
   
A palindrome is a string that reads the same in both directions, for example ```z```, ```uwu```, or ```moom```.   
   
### **Input**   
The first line contains an integer t ```( 1 ≤ t ≤ 100 )``` — the number of testcases.   
   
The following ```t``` lines each contain a string of length at most ```100``` consisting of lowercase English letters.   
   
### **Output**   
For each test case, output ```"YES"``` or ```"NO"```, denoting the answer.   
   
   
## Code

```py
inputs = int(input())

for i in range(inputs):
    s1 = input()
    s2 = s1[::-1]

    if(s1 == s2):
        print("YES")
    else:
        print("NO")
```