# EXP-5b command-line-arguments-to-count-word
## Date: 10.10.2023
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import the sys module.

### Step 2: Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: Read the file using read() method.

### Step 4: Use split() method to split the file content into words.

### Step 5: Use len() to find the total words.

### Step 6: Run the program to determine the number of words in the file created.

## PROGRAM:
```
Developed by: Richardson A
Register Number: 212222233005

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))

```

### OUTPUT:

![image](https://github.com/Richard01072002/command-line-arguments-to-count-word/assets/141472248/4d5eb5b7-3178-466a-a4c4-8bf1c0c5281a)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
