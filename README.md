## DATE:
# EX.NO.10 Command line arguments to count word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
filename as the first argument after the name of script. Open the file as sys.argv[1].
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
# Program to find Command--line-arguments-to-count-word
# Developed by: POZHILAN V D
# Register no: 212223240118

import sys
fp=open(sys.argv[0])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/b137a383-3f51-49ab-bbcc-e07a55b9deb7)

![image](https://github.com/user-attachments/assets/a6096406-562a-4889-bb09-90e76eb71bb7)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
