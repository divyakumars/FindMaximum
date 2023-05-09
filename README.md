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
```
Program to mark the maximum of marks using the list method sort
Developed by: DIVYA K
RegisterNumber: 212222230035
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: DIVYA K
RegisterNumber: 21222230035
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: DIVYA K
RegisterNumber: 212222230035
'''
def max_marks(list1):
   max=list1[0]
   for i in list1:
       if i > max:
         max=i
   return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://user-images.githubusercontent.com/119393621/237037606-dc366a0e-45fb-410f-9537-5d3da0293023.png)
![image](https://user-images.githubusercontent.com/119393621/237038158-b8bde4b8-442c-4be0-a4f6-e2b250360eeb.png)


## Output:
![image](https://user-images.githubusercontent.com/119393621/237006825-b134162b-c2b0-47c8-9466-c81b48b870f8.png)
![image](https://user-images.githubusercontent.com/119393621/237030283-4c6b6e57-202f-4708-8826-2adc5f074a2d.png)
![image](https://user-images.githubusercontent.com/119393621/237037300-95c935f5-1a43-401e-9c85-35b7a3e80570.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
