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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Sanjay Balaji S
RegisterNumber: 23005804
'''
def max_marks(marks):
    marks.sort(reverse=True)
    m=marks[0]
    return m
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Sanjay Balaji S
RegisterNumber: 23005804
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Sanjay Balaji S
RegisterNumber: 23005804
'''
def max_marks(list1):
    a=list1[0]
    for i in list1:
        if i>a:
            a=i
    return a
```
## Output:
i)![image](https://github.com/SanjayBalaji0/FindMaximum/assets/145533553/922bbd0f-c8ad-47fb-a14d-7a2c7905c5a8)

ii)![image](https://github.com/SanjayBalaji0/FindMaximum/assets/145533553/622ab9c1-acc9-4f96-8275-a3b44dd7e48a)

iii)![image](https://github.com/SanjayBalaji0/FindMaximum/assets/145533553/610e84b7-30ec-4dda-bec3-c207c4560a8a)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
