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
Developed by:GAYATHRI.K 
RegisterNumber:23013439 
'''
def max_marks(marks_list):
    marks_list.sort(reverse=True)
    return marks_list[0]
    



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: GAYATHRI.K
RegisterNumber:23013439
'''
def max_marks(marks):
   return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: GAYATHRI.K
RegisterNumber: 23013439
'''
def max_marks(marks_list):
    max_value=marks_list[0]
    
    for mark in marks_list:
        if mark > max_value:
            max_value=mark
    return max_value
    
  


```
## Sample Input and Output
 ![Alt text](<Screenshot 2023-12-25 085520.png>)
![Alt text](<Screenshot 2023-12-25 085535.png>)
![Alt text](<Screenshot 2023-12-25 085550.png>)
## Output:
![Alt text](<Screenshot 2023-12-25 002351.png>)
![Alt text](<Screenshot 2023-12-25 002425.png>)
![Alt text](<Screenshot 2023-12-25 002444.png>)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.