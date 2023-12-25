# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
instalize the value for the word count as zero.
### Step 2: 
 using open command open the txt file to read
### Step 3: 
use the split() command
### Step 4:  
print the counted words
### Step 5: 
end the program 
## PROGRAM:
```
'''
Developed by:vellachi tilak
Registered number: 2122232340172
'''
num_words=0
with open('text.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))
```
### OUTPUT:
![Screenshot 2023-12-20 192818](https://github.com/Thilak45/Word-count/assets/138849161/872e2405-45c7-4b1f-9d64-44a50908443b)

![Screenshot 2023-12-20 193013](https://github.com/Thilak45/Word-count/assets/138849161/bd3e08e4-846e-43ed-be9f-9173b0ceea00)

## RESULT:
Thus the program is written to find the word count from a text.
