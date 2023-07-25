# Find the maximum of a list of numbers
## AIM:
To write a program to find the maximum of a list of numbers.
## EQUIPMENTS REQUIRED:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## PROGRAM:

i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    n=max(marks)
    return n
```

iii) # To find the maximum marks without using builtin functions.
```def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## SAMPLE INPUT AND OUTPUT:
![output](/sample1.png))
![output](/sample2.png)
![output](/sample3.png)
## OUTPUT:
![output](/output3a\)1..png)
![output](/output3a\)2..png)
![output](/output3a\)3..png)
## RESULT:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.