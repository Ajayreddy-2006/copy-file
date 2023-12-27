# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a file.
## Step 2:
Write some lines in that file.
## Step 3:
Create a python file.
## Step4:
Write a code to copy the content of the file to a new file.
## Step 5:
Run the program.
## Step 6:
Display the output.

## PROGRAM:
```
Developed By:T.Ajay
Register No: 212223230007
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![Screenshot 2023-12-27 185256](https://github.com/Ajayreddy-2006/copy-file/assets/145742508/14f934fd-5eeb-44bd-99e2-ad72e5e16060)

# Copied File:
![Screenshot 2023-12-27 185334](https://github.com/Ajayreddy-2006/copy-file/assets/145742508/c97ecffb-2b16-4354-9198-efdb9aafe16e)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
