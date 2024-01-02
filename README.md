![Screenshot 2024-01-02 235951](https://github.com/Srikaavyaathamizh/copy-file/assets/144870938/0a17c6d5-37cb-4d3a-ae9d-49b6b7d1e2e4)# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.
### Step 2: 
Using keyword "with" to open the required file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The for function is used to take each line from the main file.
### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.
## PROGRAM:
```
def copy(fname,newfile):
    with open(fname,'r')as fp:
        with open(newfile,'w')as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter as existing file: ")
newfile=input("Enter a name for new files: ")
copy(fname,newfile)

```
### OUTPUT:
![Screenshot 2024-01-02 235951](https://github.com/Srikaavyaathamizh/copy-file/assets/144870938/e4d01ecb-c75b-448d-84f3-ca29c82086bb)
![Screenshot 2024-01-03 000018](https://github.com/Srikaavyaathamizh/copy-file/assets/144870938/0ebc468a-871a-498a-abb1-b0326a977a85)
![Screenshot 2024-01-03 000028](https://github.com/Srikaavyaathamizh/copy-file/assets/144870938/4fa1aa8d-f433-4277-9039-d66869b5c031)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
