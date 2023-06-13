# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:

Open the file in read mode and handle it in test mood.

Step 2:

Read the text using read() function.

Step 3:

Split the text using space separator.We assume that words in a sentance are separted by a space character.

Step 4:

The length of the split list should equal the numbers of words in the test file.

Step 5:

You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

Step 6:

End the program.


## PROGRAM:
```
Program to count the words in a file
Developed by: M. Sanjay
Register number: 212222240090

fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words:",num_words)
```
### OUTPUT:

![Screenshot 2023-06-13 115038](https://github.com/Sanjay22006832/Word-count/assets/119830477/b223e077-952d-4b45-ac30-ee0f8a74eae5)

## RESULT:
Thus the program is written to find the word count from a text.
