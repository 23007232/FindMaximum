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
```PYTHON
Program to mark the maximum of marks using the list method sort
Developed by: pavithra p
RegisterNumber: 23007232
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
```PYTHON
''' 
Program to find the maximum marks using the list method max().
Developed by:pavithra p 
RegisterNumber: 23007232
'''
def max_marks(marks):
   large=max(marks)
   return large
```
```PYTHON
''' 
Program to the maximum marks without using builtin functions.
Developed by: pavithra p
RegisterNumber: 23007232
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Output:
## ![image](https://github.com/23007232/FindMaximum/assets/139115574/e74024e7-e5ca-4069-b316-b556ff1206ed)
## ![image](https://github.com/23007232/FindMaximum/assets/139115574/23abab40-41cf-45bc-8312-aa733d03e440)
## ![image](https://github.com/23007232/FindMaximum/assets/139115574/8d1b6246-88f1-4272-b2d0-f3ec6e4aec9b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
