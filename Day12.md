### Statement
~~~
Given a three-digit number. Find the sum of its digits.
~~~
~~~
Input
123
~~~
### Code
~~~
# Read an integer:
a = int(input())
s = 0
# Print a value:
while(a > 0):
  rem = a % 10
  s+= rem
  a = a//10
print(s)
~~~
~~~
Output
6
~~~
