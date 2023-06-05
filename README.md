# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
## DEVELOPED BY: vasanth s
## REFERENCE NUMBER: 212222110052
num_words =0
file1 = open("text.txt", "r")
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
Text File:
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")

### OUTPUT:
<img width="332" alt="1" src="https://github.com/vasanth0908/Word-count/assets/122000018/6370bab0-52cc-491e-8332-b888caa663bf">



## RESULT:
Thus the program is written to find the word count from a text.
