# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Create a file with .txt file extension.

### Step 2:  Add some texts in that file.
 
### Step 3:  Create a python file.

### Step 4: Write a code to count the number of words in that file.

### Step 5: Run the program.

### Step 6:  Display the output.

## PROGRAM:
```
def program():
    count=0
    with open("/content/god.text","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```
### OUTPUT:
![image](https://github.com/plotswag/Word-count/assets/145822344/5c2852e9-95ca-4788-adab-e36a64476b13)
## RESULT:
Thus the program is written to find the word count from a text.
