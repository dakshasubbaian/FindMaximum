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
#Program to mark the maximum of marks using the list method sort
#Developed by:Daksha Subbaian
#RegisterNumber:212223230036
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Developed by:Daksha Subbaian
#RegisterNumber:212223230036
def max_marks(marks):
    n=max(marks)
    return n
```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by:Daksha Subbaian
#RegisterNumber:212223230036
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/01bb9574-3336-4b92-9557-b779b5fa3504)
![image](https://github.com/user-attachments/assets/e3ea51ac-158c-45b2-a389-c72b23454123)
![image](https://github.com/user-attachments/assets/a427c14e-89a5-4c0c-906a-805965f07765)


## RESULT:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
