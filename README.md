# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open the file in read mode and handle it in test mood.


### Step 2:

Read the text using read() function.

### Step 3:

Split the text using space separator. We assume that words in a sentence are separted by a space character.


### Step 4:

The length of the split list should equal the numbers of words in the test file.

### Step 5:

You can refine the count by cleaning the string prior to splitting or validating the words after splitting.


### Step 6:

End the program.


## PROGRAM:
```
Developed by: DIVAKAR R
RegisterNumber: 212222240026

fname = input("Enter file name: ")
num_words = 0
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print("Number of words: ", num_words)
```
### OUTPUT:

![output](https://github.com/divakar618/Word-count/assets/121932143/fe5cabcc-228a-4427-a8be-e21426d9516c)



## RESULT:
Thus the program is written to find the word count from a text.
