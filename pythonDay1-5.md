
# Day 1

### Input two numbers and print their sum.

```python
num1 = input("enter the number1:")
num2 = input("enter the number2:")
sum = int(num1) + int(num2)
print("The sum of two numbers is "+ str(sum))
```
# Check if a number is even or odd.
num = int(input("enter the number:"))

if num%2 == 0:
    print("the given number is even")
else:
    print("the given number is 0dd")
    
# Reverse a string entered by the user.

string = "python is a programmin langauage"
rev_string = string[::-1]
print(rev_string)


# Day 2

# 4. Find the length of a given string.

string = "pavankumarsruthiramya"
length = len(string)
print(length)

# 5. Print all elements of a list.
li = [1,2,3,4,5,6,7,8]
n = len(li)
#print(n)
for i in range(n):
    print(li[i])
    
# 6. Print the list in reverse order.
empty_arr = []
for i in range(n-1,-1,-1):
    empty_arr.append(li[i])

print(empty_arr)


# Day 3
# 7. Swap values of two variables.

str1 = "van jim"
str2 = "bus rim"

temp = str1
str1 = str2
str2 = temp


print(str1,str2)

# 8. Concatenate two strings.

str1 = "Hey I am learning "
str2 = "python"
print(str1+str2)


# 9. Find the largest of three numbers.

num1 = 98
num2 = 216
num3 = 96

if num1>num2 and num1>num3:
    print("the fist number is the large one ",num1)
elif num2>num3:
    print("the second number is the large one",num2)
else:
    print("the third number is the large one",num3)
    
'''
# Day 4
# 10. Print numbers from 1 to 20 using a loop.


# 11. Print all even numbers between 1 and 50.
# 12. Sum all numbers in a list.
