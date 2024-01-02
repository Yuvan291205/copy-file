# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from one file to another file.

### Step 2:
Using key word "with" to open the required file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using "w" which is used to write only.

### Step 5:
The for fuction is used to take the each line from the main file.

### Step 6:
Write() is used to write the lines of main file to the empty file or do the directed file.

### Step 7:
Print the output.




## PROGRAM:
```
Developed By : Yuvan M
Register Number : 212223240188
with open("file.txt","r") as fp:
    with open("file1.txt","w") as fp1:
        v = fp.read()
        fp1.write(v)
```

### OUTPUT:
![output](https://github.com/Yuvan291205/copy-file/assets/138849170/7c553bd2-0ede-449e-9d11-9b48ff3625c2)
![output](https://github.com/Yuvan291205/copy-file/assets/138849170/ad9a9a66-671f-4ad8-841d-e84630acff28)


## RESULT:
Thus the program is written to copy the contents from one file to another file.


## RESULT:
Thus the program is written to copy the contents from one file to another file.
