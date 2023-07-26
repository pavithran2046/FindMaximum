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
#Program to mark the maximum of marks using the list method sort
#Developed by:s.pavithran 
#RegisterNumber: 23001643

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by: pavithran.s
#RegisterNumber: 23001643


def max_marks(mark):
    mark.sort()
    max=mark[-1]
    return max


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to the maximum marks without using builtin #functions.
#Developed by:pavithran S 
#RegisterNumber:23001643 

def max_marks(list):
    max=list[0]
    for i in list:
        if i>max:
            max=i
    return max







``` 

## Output:
![output](/img/Screenshot%202023-07-26%20100629.png)
![output](/2.png)
![output](/3.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.