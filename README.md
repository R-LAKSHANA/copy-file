# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode.

### Step 2: 
Open the second file in append mode.

### Step 3: 
Read the content in first file using for() loop.

### Step 4:  
Append the content of fist file in the second file using bulit-in function write().

### Step 5: 
End the program.

## PROGRAM:
```python
'''
Program to copy the contents from one file to another file.
Developed by: R LAKSHANA
RegisterNumber: 22004909
'''
with open("unit 4.txt","r") as file1:
    with open("copy.txt","a") as file2:
        for line in file1:
            file2.write(line)
```

## OUTPUT:

![original](/Original.png)

![copy](/Copy.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.