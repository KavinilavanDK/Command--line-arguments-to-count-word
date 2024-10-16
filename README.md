## DATE:
# EX:10 - Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.
### Step 2: 
 Create a file pointer and open the file which is passed in command line.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
## PROGRAM:
```
# Program to find Command--line-arguments-to-count-word
# Developed by: KAVI NILAVAN DK
# Register no: 212223230103

import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()


```
### OUTPUT:
![Screenshot 2024-10-16 160759](https://github.com/user-attachments/assets/6d8def37-0567-4053-a050-10e21992265d)
![329843782-cd24ef6f-5bc8-43ef-9a31-96b0080d9e0f](https://github.com/user-attachments/assets/687e038f-1cf9-4907-ac5f-f7398a17217f)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
