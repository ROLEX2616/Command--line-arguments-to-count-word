# DATE:
# EX-10 Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
 Create a text file in which words has to be counted.
### Step 3: 
Open python file in visual studio code.
### Step 4:  
Execute the program.
### Step 5: 
Print the output.
### Step 6: 
End the program.
## PROGRAM:
```

#Program for getting the word count from the contents of a file using command line arguments.
#Developed by : KAVINRAJ.S
#REG NO: 212223100019


import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))







```
### OUTPUT:
![Screenshot 2024-10-16 115900](https://github.com/user-attachments/assets/030500a4-4c07-43e9-ba46-1727e68eb0a0)

![Screenshot (133)](https://github.com/user-attachments/assets/57abd50e-0917-4d28-9822-c43f9f61c401)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
