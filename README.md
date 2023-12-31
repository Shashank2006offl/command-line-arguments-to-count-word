# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys module.
### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.

### Step 5: 
Use len() to find the total words.
## PROGRAM:
```
# Developed By: Shashank R
# Reference No: 212223230205

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![WhatsApp Image 2023-12-31 at 05 28 29_5606e7ab](https://github.com/Shashank2006offl/command-line-arguments-to-count-word/assets/147140026/32d6bb34-f301-4936-b786-de02a7c18f98)
![WhatsApp Image 2023-12-31 at 05 36 24_f0726399](https://github.com/Shashank2006offl/command-line-arguments-to-count-word/assets/147140026/403ad582-a542-4229-b327-43f808a67885)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
