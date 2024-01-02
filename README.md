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
Program to mark the maximum of marks using
the list method sort
Developed by:vignesh.v
RegisterNumber:23004027

def max_marks(marks):
      marks.sort()
      large=marks[-1]
      return large
```

ii)	# To find the maximum marks using the list method max().
```Python 
Program to find the maximum marks using
 the list method max().
Developed by:vignesh.v 
RegisterNumber:23004027

def max_marks(marks):
    max1=max(marks)
    return max1
```

iii) # To find the maximum marks without using builtin functions.
```Python 
Program to the maximum marks without using
 builtin functions.
Developed by:vignesh.v 
RegisterNumber:23004027

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
1.The maximum of marks using the list method sort.
![exa3](https://github.com/23004027/FindMaximum/assets/138956447/59b80612-4df7-450e-aa20-832e7aa775bf)

2.The maximum marks using the list method max().
![exb3](https://github.com/23004027/FindMaximum/assets/138956447/7d64f8a1-0884-444a-94d3-08679c3dc8c7)

3.The maximum marks without using builtin functions.
![exc3](https://github.com/23004027/FindMaximum/assets/138956447/4ecc670c-e1e1-4def-bba6-54dd963f197c)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
