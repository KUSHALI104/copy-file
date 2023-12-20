# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
get the file name to create user 
### Step 2: 
 give a new file name to create a copy of a file content
### Step 3: 
read the file and close the file
### Step 4:  
now the content in the new filr
### Step 5: 
when done print"File Copied Successfully"
### Step 6: 
end the program
## PROGRAM:
```
'''
#Program to copy the file.
#Developed by: KUSHALI P G
#RegisterNumber:23012804
'''
print("Enter the name of source file: ")

sFile=input()

print("Enter the name of target file: ")

tFile=input()

fileHandle=open(sFile,"r")

texts=fileHandle.readlines()

fileHandle.close()

fileHandle=open(tFile, "w")

for s in texts:

    fileHandle.write(s)

fileHandle.close()

print("\nFile Copied Successfully!")
```

### OUTPUT:
![Screenshot 2023-12-20 231500](https://github.com/KUSHALI104/copy-file/assets/150231135/b1469693-5c43-46ce-ab5a-a88efb1aa365)



![Screenshot 2023-12-20 225749](https://github.com/KUSHALI104/copy-file/assets/150231135/acde19b5-ecd5-479d-a9e6-09a10b5403f3)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
