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
![image](https://github.com/user-attachments/assets/97053e5c-0037-4579-997c-87f0c6d47dd0)
![image](https://github.com/user-attachments/assets/a77809bb-0fd3-420e-a474-9d79a8c7c0c4)
![image](https://github.com/user-attachments/assets/96ad1a89-f5ad-4b8c-b3dc-49c9533c097b)

## RESULT:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
