
### Statement
~~~
Instructions from your teacher:
JugsMugs for Three and Five
Write a program that receives a number on the input.
If the number is a multiple of 3, it prints "Jugs".
If the number is a multiple of 5, it prints "Mugs".
If the number is a multiple of both 3 and 5, it prints "JugsMugs".
Otherwise, it prints the number.
~~~
~~~
INPUT 
3 
OUTPUT
Jugs
INPUT 
15
OUTPUT
Mugs
INPUT 
112
OUTPUT
112
~~~
### code
~~~
ip = int(input())
if ( ip%3 == 0 and ip%5 == 0 ):
  print("JugsMugs")
elif ( ip%5 == 0):
  print("Mugs")
elif ( ip%3 == 0):
  print("Jugs")
else:
  print(ip)
~~~
