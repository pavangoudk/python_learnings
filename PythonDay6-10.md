
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


