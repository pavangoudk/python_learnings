
# Day 1

### 1.Input two numbers and print their sum.

```python
num1 = input("enter the number1:")
num2 = input("enter the number2:")
sum = int(num1) + int(num2)
print("The sum of two numbers is "+ str(sum))
```
### 2.Check if a number is even or odd.

```python
num = int(input("enter the number:"))

if num%2 == 0:
    print("the given number is even")
else:
    print("the given number is 0dd")
```
    
### 3.Reverse a string entered by the user.
```python
string = "python is a programmin langauage"
rev_string = string[::-1]
print(rev_string)
```

# Day 2

### 4. Find the length of a given string.
```python
string = "pavankumarsruthiramya"
length = len(string)
print(length)
```
### 5. Print all elements of a list.
```python
li = [1,2,3,4,5,6,7,8]
n = len(li)
#print(n)
for i in range(n):
    print(li[i])
 ```   
### 6. Print the list in reverse order.
```python
empty_arr = []
for i in range(n-1,-1,-1):
    empty_arr.append(li[i])

print(empty_arr)
```
# Day 3
### 7. Swap values of two variables.
```python
str1 = "van jim"
str2 = "bus rim"

temp = str1
str1 = str2
str2 = temp

print(str1,str2)
```
### 8. Concatenate two strings.
```python
str1 = "Hey I am learning "
str2 = "python"
print(str1+str2)
```

### 9. Find the largest of three numbers.
```python
num1 = 98
num2 = 216
num3 = 96

if num1>num2 and num1>num3:
    print("the fist number is the large one ",num1)
elif num2>num3:
    print("the second number is the large one",num2)
else:
    print("the third number is the large one",num3)
```
# Day 4
### 10. Print numbers from 1 to 20 using a loop.
```python
for i in range(25):
    print("using for loop",i)
```

### 11. Print all even numbers between 1 and 50.
```python
for num in range(51): 
    if num%2 == 0:
        print(num,"num is even")
    else:
       continue   # after this statment the code won't execute it will start from first again 
       print(num,"num is 0dd")
```
### 12. Sum all numbers in a list.
```python
numbers = [1, 2, 3, 4, 5]
count = 0
for i in range(len(numbers)):
    count += numbers[i]
print("the sum of all numbers in the list is ", count)    
```
#Day 5

###13. Count the number of words in a sentence.

```python
string = "I am interested in python programming language"
str_split = string.split()
print(str_split)
print("the count of all words in the string  is ", len(str_split))    
```
###14. Find the minimum value in a list.

```python
li = [6,2,3,4,5,1,9,7,8]
min_arr=li[0]
for i in range(len(li)):
    print("value going in",li[i])
    print("iteration",i)
    print(li[i],">",min_arr) #checking 
    if li[i]>min_arr:
       min_arr = li[i]

print("min value in list",min_arr)
```
###15. Print every character of a string on a new line.
```python
string = "every character of a string on a new line"
for char in string:
    print(char)
```

