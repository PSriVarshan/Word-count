# Word-count

## AIM:

To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:

Open visual studio code

### Step 2: 

Create file with .py extension.
 
### Step 3: 

Start the program.

### Step 4:  

Write the code.

### Step 5: 

Run terminal for output of the given program.

### Step 6: 

End the program

## PROGRAM:

```
'''
Developed by : P Sri Varshan
Register name : 22008051
'''
num_words = 0
with open('data.txt','r') as f1:
     for i in f1:
        words=i.split()
        num_words+= len(words)
print("Number of words in the files = {}".format(num_words))

```


### OUTPUT:

#### Text File

![5a data](https://user-images.githubusercontent.com/114944059/214645414-4181382d-344d-4bb7-8438-25f31a04a519.png)

#### Code Output

![5A SRI](https://user-images.githubusercontent.com/114944059/214645815-e1fd3c69-4597-4b23-8236-c8be7782cd9c.png)



## RESULT:
Thus the program is written to find the word count from a text.
