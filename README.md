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
Developed by:Mohammed Faizal.J
RegisterNumber: 22003412
'''
def max_marks(marks):
        marks.sort()
        return marks[-1]
        
    
    


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Mohammed Faizal.J
RegisterNumber: 22003412
'''
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Mohammed Faizal.J
RegisterNumber: 22003412
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i >max1:
            max1 = i
    return max1
    


```
## Sample Input and Output
![a](https://user-images.githubusercontent.com/120553195/214830616-4efad35f-ffd1-4a25-b06c-6c42822c5468.png) 

## Output:
![b](https://user-images.githubusercontent.com/120553195/214830568-66eccc81-2dfc-4e6f-8699-4008c41a3d2f.png)
![b](https://user-images.githubusercontent.com/120553195/214830568-66eccc81-2dfc-4e6f-8699-4008c41a3d2f.png)
![b](https://user-images.githubusercontent.com/120553195/214830568-66eccc81-2dfc-4e6f-8699-4008c41a3d2f.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
