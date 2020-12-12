## Beginner - Python Loops

indentation is important.

	>>> # Measure some strings:
	... words = ['cat', 'window', 'defenestrate']
	>>> for w in words:
	...     print(w, len(w))
	...
	cat 3
	window 6
	defenestrate 12
    enter code here

student_heights = input("Input a list of student heights ").split()

for n in range(0, len(student_heights)):

student_heights[n] = int(student_heights[n])



	total_height = 0;
	for height in student_heights:
	 total_height +=height;
	avg = (total_height/len(student_heights));
	print(round(avg))
**The  [`range()`]**

    >>> for i in range(5):
    ...     print(i)
    ...
    0
    1
    2
    3
    4

       range(5, 10)
       5, 6, 7, 8, 9

    range(0, 10, 3)
       0, 3, 6, 9

    range(-10, -100, -30)
      -10, -40, -70

    >>> print(range(10))
    		range(0, 10)  // NOTE
   	>>> sum(range(5))
   		10

**FizzBuzz**
https://repl.it/@MathankumarS/day-5-4-exercise#README.md

**Password Generator Project**
https://repl.it/@MathankumarS/password-generator-start#main.py
