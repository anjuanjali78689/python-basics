# python basics

## Data Types ::  defines the type of data stored in variable
1.Write a program to check the data type of the following:
25
"Hello"
3.14
True

  ```python
   num1 =25
   name = "Hello"
   num2 = 3.14
   val = True
   print(type(num1),"\n",type(name),"\n",type(num2),"\n",type(val))
  ```
2.Create variables of these types:
  Integer
  Float
  String
  Boolean

  ```python
   num1=10
   num2=3.14
   name="Python"
   val=False
   print( num1,num2,name,val,sep ="\n")
  ```
# Conversion of data types
1.Convert an integer into float and print it.

  ```Python
   a = input("enter the integer value")
   print(float(a))
  ```
2.Convert a string "100" into integer and also write code to check  current and coverted data type

 ```python
  a ="100"
  b=int(a)
  print(type(a),b,type(b),sep="\n")
