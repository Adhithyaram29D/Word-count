# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the created file.
### Step 2: 
 Use the split function to split the words.
### Step 3: 
Find the length of the words using len() function.
### Step 4:  
Print the number of words in the file.
## PROGRAM:
```python
#Developed By: AdhithyaRam D
#Register No: 212222230008
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
![Screenshot 2023-06-08 223017](https://github.com/Adhithyaram29D/Word-count/assets/119393540/4f54eacd-e439-43c1-9f03-f1b22bc9eb1d)

## RESULT:
Thus the program is written to find the word count from a text.
