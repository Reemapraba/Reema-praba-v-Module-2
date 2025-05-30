# Reema-praba-v-Module-2
# 19CS301-Module2
### Register No - 212222020020
### Name - Reema praba

# ExNo: 2.1 ITERATIVE STATEMENTS
### Aim: To write Python Program to print numbers  range from M to N (including M and N values)
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create variables `a` and `b`.

**STEP 3:** Get the values of `a` and `b` from the user.

**STEP 4:** Use a `for` loop to iterate from `a` to `b` (inclusive).

**STEP 5:** Print each number in the range.

**STEP 6:** Stop.

### Program:
```
a = int(input())
b = int(input())
for i in range (a , b+1):
       print(i)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/d9ab13a0-d655-43cf-a863-8987ab5dda00)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 2.2 Functions
### Aim: To write a python program to define a function named "result" that accepts 2 values and return its sum, subtraction and multiplication.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create variables `a` and `b`.

**STEP 3:** Get the values of `a` and `b` from the user.

**STEP 4:** Define a function `result(a, b)` to perform the following:
- Calculate the sum of `a` and `b`.
- Calculate the subtraction of `a` and `b`.
- Calculate the multiplication of `a` and `b`.
- Print the results using formatted output.

**STEP 5:** Call the function `result(a, b)`.

**STEP 6:** Stop.

### Program:
```
def result(a,b):
    sum = a+b
    sub = a-b
    mul = a*b
    print ("Sum is {},Sub is {},&Multiply is {}".format(sum,sub,mul))
a = int(input())
b = int(input())

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/c5e85696-6186-44cb-b0c5-122ea1db4345)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 2.3 Built-In Function and Lambda Function
### Aim: To write a python program to convert the decimal number to binary number using built in functions.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a variable `a`.

**STEP 3:** Get the value of `a` from the user.

**STEP 4:** Convert the value of `a` to binary using the `bin()` function.

**STEP 5:** Print the binary value.

**STEP 6:** Stop.

### Program:
```
a = int(input())
print (bin(a))

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/03ae217a-f5f0-42ea-856f-f3852a9a3c57)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 2.4 Looping Patterns
### Aim: To write a Python program to print alternate number pattern .Get the number of rows as input
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a variable `rows`.

**STEP 3:** Get the value of `rows` from the user.

**STEP 4:** Define a function `altr_pattern(rows)` to print the pattern.

**STEP 5:** Inside the function:
- Initialize a variable `num` to 1.
- Use an outer loop from 1 to `rows`:
  - Use an inner loop from 1 to the current outer loop index:
    - Print `num` with a space.
  - Increment `num` by 2 after each outer loop iteration.
  - Print a new line after each row.

**STEP 6:** Call the function `altr_pattern(rows)`.

**STEP 7:** Stop.

### Program:
```
def altr_pattern(rows):
    num = 1
    for i in range (1 , rows+1): 
         for j in range (1, i+1):
             print(num, end=" ")
         num +=2
         print()
rows = int(input())
altr_pattern(rows)

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/9dd98d55-f6e4-4799-b0f7-86f2b44241d1)

### Result: Thus, the given program is implemented and executed successfully .
Ex No:2.5 SEB-Sum of odd numbers

## Aim:
To write a python Program to find the sum of series 1+3+5+7.......+N

## Algorithm:
1. Start.
2. Accept input `N` from the user.
3. Initialize a variable `sum` to 0.
4. Loop `i` from 1 to `N` (inclusive):
   - If `i` is odd (i.e., `i % 2 != 0`), add it to `sum`.
5. After the loop ends, display the final value of `sum`.
6. End.

## Program:
```
a = int(input())
sum = 0
for i in range(1, a + 1):
    if i % 2 != 0:
        sum += i
print("The sum of the series = ", sum)
```
### Output:
![image](https://github.com/user-attachments/assets/15b08c4a-d7fc-43cc-8d8a-ca676f0d05af)

### Result: Thus the given code was executed successfully.

