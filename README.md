# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4:  
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The four function is used to take each line from the main file.

### Step 6: 
End the program.


## PROGRAM:
```
#Program for copying the contents from one file to another file
#Developed by: MANIKUMAR DK
#RegisterNumber: 212223230121

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)

```

### OUTPUT:
![Screenshot 2024-05-11 200651](https://github.com/MANIKUMARDK/Copy-File/assets/147215581/1229206a-ebb0-472d-9b82-2f30ee243c41)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
