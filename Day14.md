### Statement
~~~
Given three integers, print the least of them.
~~~
~~~
Input
5
3
7
~~~
### Code
~~~
# Read an integer:
a = int(input())
b = int(input())
c = int(input())

if(a < b and a < c):
  print(a)
elif(b < c):
  print(b)
else:
  print(c)
~~~
~~~
Output
3
~~~
