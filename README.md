# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create two empty files.

Step 2:
In one file.txt enter some content and save the file.

Step 3:
In other file1.txt file read the file.txt using .read() build in function.

Step 4:
Next ope file1.txt in write mode.

Step 5:
Copy file.txt using copy() funtion.

Step 6:
Run the program.
## PROGRAM:
```
Devloped by:m.d.harini
ref no.:22001980
with open('myfile.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
            
### OUTPUT:
![image](https://user-images.githubusercontent.com/113497680/192234998-6d1d7b91-f96c-4e60-9a9e-89e6855d1591.png)
![Screenshot from 2022-09-26 13-43-29](https://user-images.githubusercontent.com/113497680/192235042-cf4b48de-b801-4eb5-932a-73ec3fd09946.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
