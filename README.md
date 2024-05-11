# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().
### Step 3: 
The number of rows returned is defined in Pandas option settings.
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame.


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
