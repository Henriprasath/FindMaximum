# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum valuea
## Program:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: HENRIPRASATH.S
RegisterNumber:23003595
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large    
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: HENRIPRASATH.S
RegisterNumber:23003595
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large 
```

iii) # To find the maximum marks without using builtin functions.
``` 
Program to the maximum marks without using builtin functions.
Developed by: HENRIPRASATH.S
RegisterNumber:23003595
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max=i
    return max    
```
## Output:
![Screenshot 2023-12-29 172630](https://github.com/Henriprasath/FindMaximum/assets/144979077/a5c58f60-c560-45ac-b7c3-888964bc54c7)
![Screenshot 2023-12-29 172648](https://github.com/Henriprasath/FindMaximum/assets/144979077/de324678-cefb-41d6-855b-5072225a27ca)
![Screenshot 2023-12-29 172718](https://github.com/Henriprasath/FindMaximum/assets/144979077/4a298c6c-d681-48b5-9729-192388746770)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
