# python-basics
Python basics practice including variables, data types, operators, and input/output programs.

## Variable
1.Write a Python program to create a variable name and store your name in it. Print the variable.

   ```python
    name = "Anjali"
    print(name)
   ```
2.Create two variables  and print their sum

   ```python
    num1 = int(input("enter the number"))
    num2 = int (input("enter the number"))
    print(num1+ num2)
   ```
3.Swap two variables without using a third variable.

   ```python
    a = int(input("enter a value : "))
    b = int(input("enter b value : "))
    a = a+b
    b = a-b
    a=a-b
    print("a :",a)
    print("b :",b)
   ```
4.Write a program to store your name, age, and city in variables and print them in one sentence.

   ```python
   a,b,c =input("enter the name : "),input("enter the age : "),input("enter the city : ")
   print("My name is",a,"age is",b,"and live in",c)
  ```

### Data Types
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
