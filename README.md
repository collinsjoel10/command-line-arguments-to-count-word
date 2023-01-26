# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
import sys

Step 2:
Open file using open().

Step 3:
Use for loop.

Step 4:
Use len to count number of words.

PROGRAM:
```
#program is developed: joel p
# REF.NO: 22008934
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: joel p")
print("word count in file = ",count)
```

### OUTPUT:
![4891f339-3d75-43d8-bbe9-27e734d87d7c](https://user-images.githubusercontent.com/118626456/214858426-bd823a6c-f4bd-4f4b-88c5-e0b913825309.jpg)

![7ee2cf02-4514-4a79-b300-83d9f377dd40](https://user-images.githubusercontent.com/118626456/214858436-8429bdf9-c2f3-4f11-829e-1be767f8cbe8.jpg)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
