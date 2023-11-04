# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode. 
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.

## PROGRAM:
```
#Developed By: SWETHA.S
#Register No: 212222230155
with open('f11.txt','r') as f1:
    with open ('f12.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
FILE1:

![Screenshot 2023-11-04 174340](https://github.com/swethaselvarajm/copy-file/assets/119525603/c7ea68cd-7200-414e-8953-64e1c85c41fc)

FILE2:

![Screenshot 2023-11-04 174352](https://github.com/swethaselvarajm/copy-file/assets/119525603/702f6a3e-eb71-4407-a30b-64354ff0bd74)

FILE1 COPIED INTO FILE2:

![Screenshot 2023-11-04 174238](https://github.com/swethaselvarajm/copy-file/assets/119525603/63382a19-217f-4f85-ab64-aef905de9980)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
