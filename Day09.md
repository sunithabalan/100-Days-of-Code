### Statement
~~~
Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. 
The moment of the first timestamp happened before the moment of the second one. 
Calculate how many seconds passed between them.
~~~
~~~
Input
Example input #1 1 1 1 2 2 2
Example input #2 1 2 30 1 3 20
~~~
### Code
~~~
# Read an integer:
hours_one = int(input())
minutes_one = int(input())
seconds_one = int(input())
hours_two = int(input())
minutes_two = int(input())
seconds_two = int(input())

# Print value:
sec1 = hours_one * 3600 + minutes_one * 60 + seconds_one
sec2 = hours_two * 3600 + minutes_two * 60 + seconds_two
print(sec2 - sec1)
~~~
~~~
Output
Example output #1 3661
Example output #2 50
~~~
