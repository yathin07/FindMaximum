# Ex - 6 
# Find the maximum of a list of numbers 
# Aim :
To write a program to find the maximum of a list of numbers.
# Equipment’s required :
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm :
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
# Program :
## i) To find the maximum of marks using the list method sort
```
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```
## ii) To find the maximum marks using the list method max()
```
def max_marks(marks):
    large = max(marks)
    return large
    
```

## iii) To find the maximum marks without using builtin functions
```
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
```
# Output :
## i) To find the maximum of marks using the list method sort

![Ex - 6 (Image-1)](https://github.com/user-attachments/assets/645f8c50-746e-4b9e-9b0f-2f1f16517f02)

## ii) To find the maximum marks using the list method max()

![Ex - 6 (Image-2)](https://github.com/user-attachments/assets/ed46dbde-f331-4b8e-af33-369dde63e1cf)

## iii) To find the maximum marks without using builtin functions

![Ex - 6 (Image-3)](https://github.com/user-attachments/assets/ab6a5870-2a5d-48bc-8eb0-e23b1826ce70)

# Result :
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
