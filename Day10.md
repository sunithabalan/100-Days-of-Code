### Statement
~~~
Given the integer N - the number of seconds that is passed since midnight - how many full hours and full minutes are passed since midnight?
The program should print two numbers: the number of hours (between 0 and 23) and the number of minutes (between 0 and 1339).
For example, if N = 3900, then 3900 seconds have passed since midnight. 
Therefore, the time now is 1:05am. 
So the program should print 1 65 - 1 full hour is passed since midnight, 65 full minutes passed since midnight.
~~~
~~~
Input
3900
~~~
### Code
~~~
# Read an integer:
n = int(input())
# 0. Name your variables properly so that the name 
#    indicates what value they contain 
# 1. If you don't about snake_case, read about it 
#    at https://en.wikipedia.org/wiki/Snake_case
# 2. Ask your mentor what "naming convention" means
# 3. Use a minimum of three variables and print using 
#    those variables 

minutes = n // 60
hours = minutes // 60
print(str(hours) +" "+ str(minutes))
~~~
~~~
Output
1 65
~~~
