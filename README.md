# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mode
# Step 2: 
Read the text using read() function.
 
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character

### Step 4:  
The length of the split list should equal the numbers of words in the test file


### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting

### Step 6: 
End the program.

## PROGRAM:
Developed by : SHEETAL.R
Registered number: 212223230206

def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)

### OUTPUT:
![Screenshot 2024-05-09 105906](https://github.com/Sheetalshee/Word-Count/assets/144979107/a5750df9-65e6-412a-a7d5-91684018e274)
![Screenshot 2024-05-09 110012](https://github.com/Sheetalshee/Word-Count/assets/144979107/93af050f-7a2d-47ff-9570-6c31968b3c32)




## RESULT:
Thus the program is written to find the word count from a text.
