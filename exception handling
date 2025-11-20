Program 1:  ZeroDivisionError

n = 10
try:
    res = n / 0
except ZeroDivisionError:
    print("Can't be divided by zero!")
**************
Program 2: # Syntax Error (Error)

try :
print("Hello world"  
except SyntaxError:
	print(“Verify the line try section properly closed or not ”)
******************
Program 3 ValueError

try:
    x = int("str")  # This will cause ValueError
    inv = 1 / x  # Inverse calculation

except ValueError:
    print("Not Valid! Give only integer input")

except ZeroDivisionError:
    print("Zero has no inverse!")

*******************
Program 4 try to understand the error possibility 

try:
   n = 0
   res = 100 / n
except ZeroDivisionError:
   print("You can't divide by zero!")
   n = int(input('enter value '))#GIVE INPUT AS a then check the program 
   res = 100 / n
   print(res)
except ValueError:
   print("Enter a valid number!")

else:
   print("Result is", res)

finally:
   print("Execution complete.")

Type the following in output :  

You can't divide by zero!
enter value a
Enter  only  numbers except 0 !
enter value 7
14.285714285714286
Execution complete.
*************
Catching Multiple Exceptions
Program 5.1

a = ["10", "twenty", 30]  # Mixed list of integers and strings
try:
    total = int(a[0]) + int(a[1])  # 'twenty' cannot be converted to int
    
except (ValueError, TypeError) as e:
    print("Error", e)
    
except IndexError:
    print("Index out of range.")
*********************
Program 5.1 alternate ‘[expanded]
a = ["10", "twenty", 30]  # Mixed list of integers and strings
try:
   total = int(a[0]) + int(a[1])  # 'twenty' cannot be converted to int
   print (total)
except  TypeError :
   print("ERROR DUE TO type")
except ValueError  :
   print("ERROR DUE TO value error")

except IndexError:
   print("Index out of range.")

************************

Program 6.

# ZeroDivisionError (Exception)  Exception as e:

n = 10
res = n / 0

try:
    numerator = int(input("Enter a numerator: "))
   denominator = int(input("Enter a denominator: "))
   result = numerator / denominator
except ValueError:
   # Handles invalid input (e.g., non-integer)
   print("Invalid input. Please enter an integer.")
except ZeroDivisionError:
   # Handles division by zero
   print("Error: Cannot divide by zero.")
except Exception as e:
   # Catches any other unexpected exceptions
   print(f"An unexpected error occurred: {e}")
else:
   # Executed if no exception occurred in the try block
   print(f"The result of the division is: {result}")
finally:
   # Always executed, regardless of exceptions
   print("Program execution completed.")

*********************
Program 7   exception using file 
run this program with non existing file 

try:
file = open(“example.txt”, “r”)
# Code to read from the file
except FileNotFoundError:
print(“File not found!”)
Else : 
file = open(“example.txt”, “r”)
print(f.read())
finally:
file.close()
******************
Program 8 Exception using Function 
def divide(x, y):
  try:
      result = x / y
  except ZeroDivisionError:
      print "division by zero!"
  else:
      print "result is", result
  finally:
      print "executing finally clause"

divide(12,0)
divide("12","2") #No 'TypeError' exception caught in this case.

**********************
Program 9 1 & program 9.2

def divide_num(num_list):
  for num in num_list:
    print(10/num)

num_list = [5, 6, 0, 7]
divide_num(num_list)


def divide_num(num_list):
  for num in num_list:
    try:
      print(10/num)
    except ZeroDivisionError as error:
      print(error)
      print('Zero is not a valid argument here')
    else:
      print('in else block')

num_list = [5, 6, 0, 7]
divide_num(num_list)


Output : 
2.0
1.6666666666666667
ZeroDivisionError: division by zero


2.0
in else block
1.6666666666666667
in else block
division by zero
Zero is not a valid argument here
1.4285714285714286
in else block

************************
Program 10 

def divide_num(num):
  try:
    f = open("testfile", "a")
    r = 10/num
    f.write("Result 10/%d is %d" %(num,r))
  except ZeroDivisionError as error:
    print(error)
    print('Zero is not a valid argument here')
  except FileNotFoundError as error:
    print(error)
    print('Passed file does not exist')

  finally:
    print('closing file')
    f.close()

divide_num(0)
