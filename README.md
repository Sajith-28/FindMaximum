## NAME : SAJITH AHAMED F
## REG NO : 212223240144
## DATE : 23/03/2024

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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```



## Output:
### OUTPUT 1 :
<img width="720" alt="Screenshot 2024-03-24 153255" src="https://github.com/Sajith-28/FindMaximum/assets/149937471/f3bb7a55-3ad0-4c64-9278-2c4d9112a762">

### OUTPUT 2 :
<img width="718" alt="Screenshot 2024-03-24 153240" src="https://github.com/Sajith-28/FindMaximum/assets/149937471/42f50a39-833f-42b4-b362-2cd8b3d8d29d">

### OUTPUT 3 :
<img width="722" alt="Screenshot 2024-03-24 153228" src="https://github.com/Sajith-28/FindMaximum/assets/149937471/c4d2b98e-b594-421c-bd4c-569f97e4dc33">



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
