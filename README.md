# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: M B ANU VARSHINI
RegisterNumber: 23008712 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: M B ANU VARSHINI 
RegisterNumber: 23008712
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: M B ANU VARSHINI
RegisterNumber: 23008712
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![max1](https://github.com/anu-varshini11/FindMaximum/assets/138969827/10ccc412-175e-4faa-8274-77b38622a7f0)
![max2](https://github.com/anu-varshini11/FindMaximum/assets/138969827/dd97f63c-36b4-4b97-9775-8b6ce1885a83)
![max3](https://github.com/anu-varshini11/FindMaximum/assets/138969827/edcb11bd-5c2e-4971-bc43-a0629a8552c3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
