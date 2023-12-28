# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 open the file and assign it to f1
### Step 3: 
read the file and assign it to data
### Step 4:  
split the data(data split())
### Step 5: 
print the word count by len(word)
### Step 6: 
close the file f1
## PROGRAM:
```
#python program for word count
#developed by:Roshini.S
#Register number:23008859

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```
### OUTPUT:
![Screenshot 2023-12-28 210338](https://github.com/23008859/command-line-arguments-to-count-word/assets/139117979/2bfad1a5-4ef2-4270-8764-dc56b436c471)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
