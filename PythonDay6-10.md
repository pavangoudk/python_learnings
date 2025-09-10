
# Day 6
### 16. Find the maximum in a list.
```python
li = [6,2,3,4,5,1,9,7,8]
max_arr=li[0]
for i in range(len(li)):
    if li[i]>max_arr:
       max_arr = li[i]

print("max value in list",max_arr)
```
### 17. Implement FizzBuzz from 1 to 50.
```python
#It is a leet code problem . divisible by 3 or 5
# Input: n = 3
# Output: ["1","2","Fizz"]

n = 10
emp_arr = []
for i in range (1,n+1):
    if i%3 == 0 and i%5 == 0:
        emp_arr.append("FizzBuzz")
    elif i%3 == 0:
        emp_arr.append("Fizz")
    elif i%5 == 0:
        emp_arr.append("FizzBuzz")
    else:
        emp_arr.append(str(i))

print(emp_arr)
```

### 18. Count vowels in a string.
```python
string = "pythonprogramming"
count = 0
for char in string:
    if char == "a" or char =="e" or char =="i" or char == "o" or char == "u":
        count += 1

print(count)   
```
### Method2
```python
vowels = "aeiouAEIOU"
string = "PavanPythonPractice"
count = 0
for char in string:
    if char in vowels:
        print(char)
        count += 1

print(count)   
```

# Day 7
### 19. Check if a number is prime.
```python
import math
from math import sqrt
n= 53
flag = 0

if n>1:
    for i in range(2,int(math.sqrt(n)) + 1):
        if n%i == 0: 
            flag = 1
            break
    if (flag == 0):
        print(n,"True", "it'a a prime")
    else:
         print(n,"False","it's not prime")
else:
    print("False")
  
 ```       
### 20. Print all prime numbers up to 100.
``` python
import math
from math import sqrt
#n= 53
#flag = 0
for n in range(1,5):
    flag = 0
    if n>1:
        for i in range(2,int(math.sqrt(n)) + 1):
            if n%i == 0: 
                flag = 1
                break
        if (flag == 0):
            print(n,"True", "it'a a prime")
        else:
             print(n,"False","it's not prime")
    else:
        print("False")    
```
### 21. Find the sum of digits of a number.
```python
number = 5050505
string = str(number)
a = len(string)
print(a)
count = 0
for n in string:
    count = count+int(n)

print(count)    
```
### Method2
```python
def sum_of_digits(n):
    total = 0
    for digit in str(abs(n)):  # Handles negative numbers as well
        total += int(digit)
    return total

# Example usage:
number = 12345
print(sum_of_digits(number))  # Output: 15
```
# Day 8
### 22. Remove duplicates from a list.
```python
my_list = [1, 2, 2, 3, 4, 4, 5]
unique = set(my_list)
print(unique)
```
### 23. Sort a list in ascending order.
```python
my_list = [4, 8, 2, 7, 5, 11, 9]
my_list.sort()
print(my_list)
```

### 24. Find the second largest number in a list.
```python
my_list = [1, 2, 2, 3, 4, 4, 5]
unique = set(my_list)
res = list(unique)
print(res[-2])
```
