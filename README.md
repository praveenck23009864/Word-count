# 5a. Word-count
## Date: 26.09.2023
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open then required file by using the function"with"
### Step 2: 
Using split function to split the words.
### Step 3: 
Finding the length of the words by using len() function.
### Step 4:  
Calling the function and printing the number of words.
## PROGRAM:
```
fname = input('Enter file name: ')
num_word = 0
with open(fname, 'r') as f:
    for line in f:
        word = line.split ()
        num_word += len(word)
print('Number of words: ', num_word)
```
### OUTPUT:
![WhatsApp Image 2023-11-17 at 23 27 02_341209fa](https://github.com/praveenck23009864/Word-count/assets/141472050/361635b5-ffc7-4525-8f76-1f7ec94acb24)

![WhatsApp Image 2023-11-17 at 23 27 02_e0245781](https://github.com/praveenck23009864/Word-count/assets/141472050/9f51efed-6ea7-4411-9bd3-b3f6c85f7fc7)

## RESULT:
Thus the program is written to find the word count from a text.
