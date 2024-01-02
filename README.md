# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
Get the file name from the user.
### Step 3: 
Read the file.
### Step 4:  
Use for loop and split.
### Step 5: 
Print the number of words.
### Step 6: 
End the program.

## PROGRAM:
### Program to find the Word Count using command line arguements.
### Developed by : JOTHIKRISHNAA V
### Register Number : 212223100017
fname=input("Enter the file name")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
### OUTPUT:

![command line](<Screenshot 2024-01-02 170415.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
