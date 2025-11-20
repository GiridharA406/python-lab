File Handling : 

Create a file called my_data.txt   already and have some content in the file then work in python compiler
Read operation with r mode 

# Open the file in read mode ('r').
file_object = open("my_data.txt", "r")

print("Content of 'my_data.txt':")

# Read the entire content of the file.
file_content = file_object.read()
print(file_content)

# Close the file.
file_object.close()


********************************************************
Opening a Python File Using with...open
In Python, there is a better way to open a file using with...open. For example,

with open("file1.txt", "r") as file1:
    read_content = file1.read()
    print(read_content)
***********************************

Write () operation with w   mode 
# Open the file in write mode ('w'). If the file doesn't exist, it will be created.
# If it exists, its content will be truncated.
file_object = open("my_data.txt", "w")

print("Enter lines to write to the file. Type 'exit' to stop.")

while True:
    line = input("Enter line: ")
    if line.lower() == 'exit':
        break
    file_object.write(line + "\n") # Add a newline character after each line

# Close the file to save the changes and release resources.
file_object.close()

print("Data written to 'my_data.txt' successfully.")
******************8

Append operation with a mode

# Open the file in append mode ('a'). If the file doesn't exist, it will be created.
file_object = open("my_data.txt", "a")

print("Enter lines to append to the file. Type 'exit' to stop.")

while True:
    line = input("Enter line to append: ")
    if line.lower() == 'exit':
        break
    file_object.write(line + "\n")

# Close the file.
file_object.close()

print("Data appended to 'my_data.txt' successfully.")
***************************8

Write a program to write the sentences given below the fi le Demo1.txt.
Hello, How are You?
Welcome to The chapter File Handling.
Enjoy the session.


def main():
obj1 = open(“Demo1.txt”,”w”) #Opens file in Write mode
obj1.write(“ Hello, How are You ? \n”)
obj1.write(“ Welcome to The chapter File Handling. \n “)
obj1.write(“ Enjoy the session. \n “)
obj1.close()
main() # Call to main function
********************************

Writing Numbers to a File

def main():
obj1 = open(“Demo1.txt”,”w”) #Open file in Write mode
for x in range(1,20):
obj1.write(x) #Write number X to a file
obj1.close()
main()
#Error
Traceback (most recent call last):
File “C:\Python34\Demo1.py”, line 6, in <module>
main()
File “C:\Python34\Demo1.py”, line 4, in main
obj1.write(x)
TypeError: must be str, not int
    So how to avoid error 
Write numbers from 1 to 20 to the output fi le WriteNumbers.txt.

def main():
obj1 = open(“WriteNumbers.txt”,”w”) #Open File in Write mode
for x in range(1,21): # Iterates from 1 to 20
x=str(x) # Convert Number to String
obj1.write(x) # Write Number to a output file
obj1.write(“ “) # Space to separate Numbers
obj1.close() # Close File
main() # Call to main function
****************************************

Generate 50 random numbers within a range 500 to 1000 and write them to fi le

WriteNumRandom.txt.

from random import randint # Import Random Module
fp1 = open(“WriteNumRandom.txt”,”w”) # Open file in write mode
for x in range(51): #Iterates for 50 times
x = randint(500,1000) #Generate one random number
x = str(x) #Convert Number to String
fp1.write(x + “ “) #Write Number to Output file
fp1.close() #Finish Writing Close the file


Reading Text from a File

>>> fp1 = open(“ReadDemo1.txt”,”r”)
There are several ways to read the content of a fi le. The two common approaches are:
a. Use read() method to read all the data from a fi le and return as one complete string.
b. Use readlines() method to read all data and return as a list of strings.

ReadDemo1.txt 

Python programming
Language 
Welcome to 
programming language

Write a program to read the content of the fi le ReadDemo1.txt using the read() method.
fp = open(“ReadDemo1.txt”,”r”) #Open file in read mode
text = fp.read() # Read Whole File exactly once
print(text) #Print the contents of file

Output

Python programming
Language 
Welcome to 
programming language
************************     OR ***************************

fp = open(“ReadDemo1.txt”,”r”)
for line in fp:
print(line)

Output : 
Python programming

Language 

Welcome to 

programming language

***************************
Write a program to read the content of the fi le ‘numbers.txt’.

fp1 = open(“numbers.txt”,”r”) #open file in read mode
num = fp1.read() #return entire contents of file as string
print(num) #print the contents of file stored in num
print(type(num)) # Check the type of num

Write a program to add the content of a fi le numbers.txt and display the sum of all the numbers present in the fi le.


fp1 = open(“numbers.txt”,”r”)
num = int(fp1.readline())
print(num)
sum = 0
print(‘The ‘, num ,’ numbers present in the file are as follows:’)
for i in range(num):
num1 = int(fp1.readline())
print(num1)
sum = sum + num1
print(‘Sum of all the numbers (except first):’)
print(sum)

Output
5
The 5 numbers present in the file are as follows:
2
4

(Contd.)

13-PY-CH_13.indd 364 01-11-2017 06:01:15

File Handling 365

6
8
10
Sum of all the numbers (except first):
30
*******************8
f = open("new.txt", "w")
while True:
    st = input("Enter next line:")
    if st == "END":
        break
    f.write(st + '\n')
f.close()

f = open("new.txt", "r")
while True:
    st = f.readline()
    if not st:
        break
    if st[0].isupper():
        print(st)
f.close()
Output
Enter next line:Hello world
Enter next line:welcome to     
Enter next line:Python programming
Enter next line:END
Hello world

Python programming
