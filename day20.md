##JugsMugsPugsPlus and Reverse
Write a program that receives a number on the input.
It also should receive another value 'rev'  (either 0 or 1) on the input. 

  - If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
  - If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
  - If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".

  - If the number is a multiple of both 3 and 5, it prints "JugsMugs".
        - also if number contains 3 and 5, it prints "JugsMugs"
  - If the number is a multiple of both 3 and 7, it prints "JugsPugs".
        - also if number contains 3 and 7, it prints "JugsPugs"
  - If the number is a multiple of 3, 5 and 7, it prints "JugsMugPugs".
        - also if number contains 3, 5 and 7, it prints "JugsMugsPugs"
```
INPUT 
73 
False  # contains 3 and 7

OUTPUT
JugsPugs

```
a = int(input())
Reverse = int(input())
if(not Reverse):
  print(
(
     ("Jugs"*(int((a%3==0) or '3' in str(a))) )
     +
    ("Mugs"*(int((a%5==0) or '5' in str(a))) )
     +
    ("Pugs"*(int((a%7==0) or '7' in str(a))) )
)
  or a
)
else:
   print(
(
     ("Pugs"*(int((a%7==0) or '7' in str(a))) )
     +
    ("Mugs"*(int((a%5==0) or '5' in str(a))) )
     +
    ("Jugs"*(int((a%3==0) or '3' in str(a))) )
)
  or a
)
