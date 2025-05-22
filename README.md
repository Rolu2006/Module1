# EX-01-PYTHON BASICS
## AIM:
To write a python program to print the result of the following expression as true or false.
```
a is True
b is False
c: 4
d: 7
```
## EQUIPMENTS REQUIRED:
1.  Hardware – PCs
2.  Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
```
1. Compare 1 == True and store the result in a.

2. Compare 1 == False and store the result in b.

3. Add True + 3 and store the result in c.

4. Add False + 7 and store the result in d.

5. Print values of a, b, c, and d with appropriate labels.
```
## PROGRAM:
```
a = (1 == True)

b = (1 == False)

c = True + 3

d = False + 7
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```
## OUTPUT:




![Screenshot 2025-05-22 213758](https://github.com/user-attachments/assets/50795d17-49a5-426f-9a64-67e86a4713be)
## RESULT:
Thus the program to print the result of the following expression as true or false has been executed successfully.


# EX-02-DATATYPES
## AIM:
To write a python program to read one integer and one float value then print the values use Eval().
```
10
12.3
```
## EQUIPMENTS REQUIRED:
1.  Hardware – PCs
2.  Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM :
1.  Take input from the user, evaluate it as a Python expression, and store in a.

2.  Take input from the user, convert it to a float, and store in b.

3.  Print the value of a.

4.  Print the value of b.

5.  End the program.
## PROGRAM:
```
a=eval(input())
b=float(input())
print(a)
print(b)
```
## OUTPUT:




![Screenshot 2025-05-22 214422](https://github.com/user-attachments/assets/8643e3eb-b4d5-4c4a-97b2-2e179c319b43)
## RESULT:
Thus the program to write a python program to read one integer and one float value then print the values use Eval() has been executed successfully.
# EX-03-VARIABLES & EXPRESSIONS OPERATOR
## AIM:
To write a python program to read the age of two persons and find who is elder and younger
## EQUIPMENTS REQUIRED:
1.  Hardware – PCs
2.  Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
1.  Read an integer input and store it in a (age of person 1).

2.  Read another integer input and store it in b (age of person 2).

3.  Compare a and b to check if person 1 is older.

4.  If a > b, print that person 1 is elder and person 2 is younger.


## PROGRAM:
```
a=int(input())
b=int(input())
if(a>b):
  print("person 1 elder")
  print("person 2 is younger")
else:
    print("person 2 elder")
    print("person 1 younger")
```
## OUTPUT:




![Screenshot 2025-05-22 214818](https://github.com/user-attachments/assets/b9a50141-7ca6-4136-91c7-546dd37b4d9b)

## RESULT:
Thus the program to write a python program to read the age of two persons and find who is elder and younger has been executed successfully.
# EX-04-CONDITIONAL STATEMENTS
## (a)
## AIM:
To write a Python program to read a number and check whether the number is divisible by 11 or not using  if else
## EQUIPMENTS REQUIRED:
1.  Hardware – PCs
2.  Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
1.  Read an integer input and store it in variable a.

2.  Check if a is divisible by 11 using the modulus operator (a % 11 == 0).

3.  If divisible, print "a is divisible by 11" using .format().

4.  Otherwise, print "a is NOT divisible by 11" using an f-string.

5.  End the program.


## PROGRAM:
```
a=int(input())
if a%11==0:
    print("{} is divisible by 11".format(a))
else:
    print(f"{a} is NOT divisible by 11".format(a))
```
## OUTPUT:




![Screenshot 2025-05-22 215210](https://github.com/user-attachments/assets/a885a600-200b-4f18-813e-5f1d56abc4ed)


## RESULT:
Thus the program to write a Python program to read a number and check whether the number is divisible by 11 or not using  if else has been executed successfully.
## (b)
## AIM:
To write a python program to check whether the user has sufficient balance or not for the withdrawal and print the account balance after the withdrawal.

Assume the initial balance be 5000 and get the withdrawal amount from the user.


## EQUIPMENTS REQUIRED:
1.  Hardware – PCs
2.  Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
1.  Set the initial account balance a to 5000.

2.  Take user input for withdrawal amount and evaluate it as b.

3.  Subtract b from a and store the result in c.

4.  If c is less than a and greater than 0, print the new account balance.

## PROGRAM:
```
a=5000
b=eval(input())
c=a-b
if c<a and c>0:
    print("Account Balance:",c)
else:
    print("Insufficient balance")
```
## OUTPUT:




![Screenshot 2025-05-22 215522](https://github.com/user-attachments/assets/c4abc972-0b64-4ebd-9d2a-0102cc075aa2)


## RESULT:
Thus the program to write a python program to check whether the user has sufficient balance or not for the withdrawal and print the account balance after the withdrawal has been executed successfully.




