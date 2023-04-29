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
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
def max_marks(marks):
    marks.sort()
    return(marks[-1])

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
def max_marks(marks):
    large=max(marks)
    return large;

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i> max:
            max = i
    return max

```

## Output:
![1](https://user-images.githubusercontent.com/119393023/235291939-aea8c014-60ad-47b6-81a6-225c5526278f.png)
![2](https://user-images.githubusercontent.com/119393023/235291971-e138845b-96fa-46f3-9030-7cc4f099d791.png)
![3](https://user-images.githubusercontent.com/119393023/235292343-d208e339-f686-4642-8c37-86a69bc99543.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
