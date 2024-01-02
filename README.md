# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create two txt file.A file which has content [sample.txt] to be copied to the empty [copy.txt]file.
### Step 2: 
 Using write() function to copy the content from sample.txt to empty file,copy.txt.
### Step 3: 
Save and run the python program to copy the content.
### Step 4:  
The text from the sample.txt file is copied to the empty file copy.txt.
### Step 5: 
Then the text is shown in empty file copy.txt. 

## PROGRAM:
```
#Program to read and copy the content in file
#Developed by:Kishan Shree 
#Register No:212223100022


def copy(fname,nfile):
    with open(fname,"r") as f:
        with open(nfile,"w") as f1:
            data1=f.read()
            f1.write(data1)
fname=input("Enter an existing file")
nfile=input("Enter a name for new file")
copy(fname,nfile)

```

### OUTPUT:
![image](https://github.com/KishanShreeB/copy-file/assets/144870434/82e6c83e-c48f-49b9-8872-7bbb6a0de990)
![image](https://github.com/KishanShreeB/copy-file/assets/144870434/4c90d8aa-98a4-42cf-b1e6-c67f6defa6cb)
![image](https://github.com/KishanShreeB/copy-file/assets/144870434/b9ac4778-5894-45cb-9bb4-03380a37cae0)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
