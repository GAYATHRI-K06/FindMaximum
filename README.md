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
 ![Screenshot 2023-12-25 085520](https://github.com/GAYATHRI-K06/FindMaximum/assets/145742742/a931fb2b-2f08-465c-8ae4-3e92f6fcc10e)
 ![Screenshot 2023-12-25 085535](https://github.com/GAYATHRI-K06/FindMaximum/assets/145742742/2cd716b6-23a2-4bb6-b862-2b7905de07e4)
 ![Screenshot 2023-12-25 085550](https://github.com/GAYATHRI-K06/FindMaximum/assets/145742742/9d9036c4-610f-4aee-8fa6-4e63114285da)


## Output:
![Screenshot 2023-12-25 002351](https://github.com/GAYATHRI-K06/FindMaximum/assets/145742742/0a3b31c1-a30d-4e79-ac06-d9f0a0938bae)
![Screenshot 2023-12-25 002425](https://github.com/GAYATHRI-K06/FindMaximum/assets/145742742/04b9d446-9eff-44d6-a9c0-5b59b1826440)
![Screenshot 2023-12-25 002425 - Copy](https://github.com/GAYATHRI-K06/FindMaximum/assets/145742742/b3f9f997-f981-406d-88df-d0042c856cdc)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
