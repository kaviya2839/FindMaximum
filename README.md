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
Developed by: Kaviya shree
RegisterNumber: 22002839
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Developed by: Kaviya shree
RegisterNumber: 22002839
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```

iii) # To find the maximum marks without using builtin functions.
```Python


''' 
Developed by: Kaviya shree
RegisterNumber: 22002839
'''
def max_marks(marks):
    large=max(marks)
    return large
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://user-images.githubusercontent.com/120553351/214812543-7d3907cd-adb2-4435-b4b2-ec5dd5ef5632.png)
![image](https://user-images.githubusercontent.com/120553351/214812626-38419b65-961c-44bb-b996-b3b7dcff9e36.png)
![image](https://user-images.githubusercontent.com/120553351/214812696-4d0f92ae-e8fe-4899-bf16-b6ddb1df901b.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
