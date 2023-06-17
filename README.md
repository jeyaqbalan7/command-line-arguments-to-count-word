# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys module

### Step 2: Open the file with sys.argv[1]
 
### Step 3: Use the for loop to select the content in file

### Step 4: Use split function to to separate the file content into words or strings

### Step 5: Count the length of the words using len

### Step 6: Print the number of words

## PROGRAM:
```
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
```

### OUTPUT:
![image](https://github.com/jeyaqbalan7/command-line-arguments-to-count-word/assets/119393851/c9ea9c16-5f8d-452c-8ca3-d82b806d1032)
![image](https://github.com/jeyaqbalan7/command-line-arguments-to-count-word/assets/119393851/ccbc695b-d3ec-4e27-982b-f703e70c40ab)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
