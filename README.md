# 5c. copy-file
## Date: 18.10.2023
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
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Darkwebnew/copy-file/assets/143114486/b811540a-1650-49f2-a308-3639782a5bb4)

![image](https://github.com/Darkwebnew/copy-file/assets/143114486/d3e3621b-d678-43f5-83af-75b387f64db8)

![image](https://github.com/Darkwebnew/copy-file/assets/143114486/b22e3476-3e89-4e35-a991-5aec9e697729)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
