# copy-file

## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file using Notepad with the file1.txt .

### Step 2:
Open Google Colab and mount the drive for using the created file in the Colab.

### Step 3:
Now open the text file in read mode.

### Step 4:
Then read the content in the file and store the data in a variable.

### Step 5:
Now open the new uncreated or an empty file using a different file object, by "w+" mode and write the content derived from first file using write().

### Step 6:
End the program



## PROGRAM:
```
#Program To write a python program for copying the contents from one file to another file.
#Developed by: Jerowin Geo J A
#Register Number: 212223100016
def fun(filename,newfilename):
    with open(filename) as fp:
        with open(newfilename,'w') as fpl:
            data=fp.read()
            fpl.write(data)
filename=input("Enter the file to read the content:")
newfilename=input("Enter the file to store copied content:")
fun(filename,newfilename)
```
### OUTPUT:
![image](https://github.com/JerowinGeo/command-line-arguments-to-count-word/assets/147139744/79d33527-7b27-48c5-a685-d37025caadd1)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
