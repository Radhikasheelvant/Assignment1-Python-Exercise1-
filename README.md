Python Exercise
Solve the following questions in jupyter notebook

PART-1
•	What are the escape sequences in Python?
Ans- 1.  \’(Single quote) – allows you to double quote
         2. \\ Backslash – 
         3. \n – New line

•	What is the result of f“{2+2}+{10%3}”?
Ans - 4+1

•	Given (name = “john smith”), what will name.title() return?
Ans – john smith
•	What does name.strip() do?
Ans – john smith
•	What is the difference between 10 / 3 and 10 // 3?
Ans – 10/3 – 3.333
           10//3 - 3


PART-2

•	What is the result of 10 ** 3?
Ans - 1000
•	Given (x = 1), what will be the value of after we run (x += 2)?
Ans - Error
•	How can we round a number?
Ans – we can use variable type to integer 
e.g. int(7.5)
•	What is the result of float(1)?
Ans – 1.0
•	What is the result of bool(“False”)?
Ans - false
•	What are the falsy values in Python?
Ans – false output is called falsy values
•	What is the result of 10 == “10”?
Ans - False
•	What is the result of “bag” > “apple”?
Ans - True
•	What is the result of not(True or False)?
Ans - True
•	Under what circumstances does the expression 18 <= age < 65 evaluate to True?
Ans – numbers between 18 to 64
•	What does range(1, 10, 2) return?
Ans – 1,3,5,7,9

•	Name 3 iterable objects in Python.
Ans – list, tuples, dictonaries, and set

PART-3

•	What are keyword arguments and when should we use them?
Ans- Values that we give while, passing into a function, are they are identified by parameter name.

•	Write a function that returns the maximum of two numbers.
a= 7
b= 8
print(max(a,b))


•	Write a function called fizz_buzz that takes a number.
1.	If the number is divisible by 3, it should return “Fizz”.
ans – x= input(“enter a number”)
if y= x/3:
    if (type(y)==int):
    print(“fizz”)

y=15/3
print(y)
if (type(y)==int):
    print("fizz")

2.	If it is divisible by 5, it should return “Buzz”.
Ans- 15/5:
    if (type(y)==int):
    print(“fizz”)

3.	If it is divisible by both 3 and 5, it should return “FizzBuzz”.
Ans - y=15/3, x= 25/5
print(y)
if (type(y)==int==0.0):
   print(“FizzBuzz”)
else:
   print(x, y) 

4.	Otherwise, it should return the same number.





1.	Write a program which contains one function named as Fun(). That function should display “Hello from Fun” on console
Ans = def fun():
                 print(“Hello from fun”)
	fun()


2.	Write a program which contains one function named as ChkNum () which accept one
 parameter as number. If number is even then it should display “Even number” otherwise display “Odd number” on console.
Ans = def ChkNum(num):
    if(num%2==0):
        print("Even number")
    else:
        print("Odd number")
print("Enter a number")
num=int(input())
ChkNum(num)

3.	Write a program which contains one function named as Add () which accepts two numbers from user and return addition of that two numbers.
Ans = def add(a,b):
    print("Addition of Number is")
print("Enter a number")
a=int(input())
print("Enter a second number")
b=int(input())
z=(a+b)
add(a,b)
print(z)

4.	Write a program which display 5 times Marvelous on screen.
Ans = for i in (1,2,3,4,5):
               print("Marvelous")

5.	Write a program which display 10 to 1 on screen.
Ans = a=[1,2,3,4,5,6,7,8,9,10]
print(a[::-1])

6.	Write a program which accept number from user and check whether that number is positive or negative or zero.
Ans = print('Enter a number')
a=int(input())
if (a>0):
    print("Positive number")
else:
    if(a<0):
        print("Negetive number")
    else:
        print("Zero number")

7.	Write a program which contains one function that accept one number from user and returns true if number is divisible by 5 otherwise return false.
Ans = print("Enter a number")
num=int(input())
if (num%5==0):
    print("True")
else:
    print("False")

8.	Write a program which accept number from user and print that number of “*” on screen.
Ans = print("Enter a number")
num=int(input())
print(num*num)

9.	Write a program which display first 10 even numbers on screen.
Ans = a=[]
for i in range(1,21):
    a.append(i)
for i in a:
    if (i%2==0):
        print(i)

10.	Write a program which accept name from user and display length of its name.
Ans = print('Enter a name')
name=str(input())
print(len(name))
