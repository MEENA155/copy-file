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
The for fuction is used to take the each linefrom the main file.
### Step 6: 
Write() is used to write the linesof main file to the empty file ordothe directed file.
## PROGRAM:
'''
Developed By Nme:S.Meena, Ref No:21500895
'''
```
with open("file1.txt","r") as fp:
    with open("file2.txt",""w") as fp1:
        v = fp.read()
        fp1.write(v)
```
### OUTPUT:

![Screenshot (103)](https://user-images.githubusercontent.com/94677128/153767631-239be692-7662-47b4-9f82-e902b51afe18.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
