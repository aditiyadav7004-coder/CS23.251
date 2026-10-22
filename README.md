<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

## School of Engineering and Technology

<br>

<img width="154" height="157" alt="Mody_University_logo" src="https://github.com/user-attachments/assets/11e32514-7869-4f2d-afc9-b45171b58488" />


<br>

# DESIGN AND ANALYSIS OF ALGORITHM PROGRAMMING LAB

### LAB RECORD

<br><br>

**Student Name:** Aditi Yadav <br>
**Enrollment Number:** 240122

<br>

**Faculty Name:** Dr. P. K. Bishnoi

<br><br>

**Mody University of Science and Technology** <br>
**School of Engineering and Technology** <br>
Lakshmangarh, Rajasthan

</div>

---

<div style="page-break-after: always;"></div>


## Assignment 1 - POSITIVE, NEGATIVE OR ZERO

## CODE:
```
n = int(input("Enter a number: "))

if n > 0:
    print("Positive number")
elif n < 0:
    print("Negative number")
else:
    print("Zero")

```

## OUTPUT:
Enter a number: 4
Positive number


## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 2 -Find the largest of three numbers using If-Else
## CODE:
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Largest number is", a)
elif b >= a and b >= c:
    print("Largest number is", b)
else:
    print("Largest number is", c)


```

## OUTPUT:
Enter first number: 4
Enter second number: 3
Enter third number: 5
Largest number is 5

## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 3 - Display the day of the week using Switch/Case

## CODE:
```
day = int(input("Enter a number from 1 to 7: "))

match day:
    case 1:
        print("Monday")
    case 2:
        print("Tuesday")
    case 3:
        print("Wednesday")
    case 4:
        print("Thursday")
    case 5:
        print("Friday")
    case 6:
        print("Saturday")
    case 7:
        print("Sunday")
    case _:
        print("Invalid day number")


```

## OUTPUT:
Enter a number from 1 to 7: 5
Friday

## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 4 - Simple calculator using Switch/Case
## CODE:
```
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = int(input("Enter your choice: "))

match choice:
    case 1:
        print("Result =", a + b)
    case 2:
        print("Result =", a - b)
    case 3:
        print("Result =", a * b)
    case 4:
        if b != 0:
            print("Result =", a / b)
        else:
            print("Cannot divide by zero")
    case _:
        print("Invalid choice")

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter first number: 4
Enter second number: 3
1. Addition
2. Subtraction
3. Multiplication
4. Division
Enter your choice: 3
Result = 12.0
>>> 

## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 5 - Multiplication table from 1 to 10 using a loop
## CODE:
```
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)

```

## OUTPUT:
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 6 - Find the sum of all even numbers from 1 to N
## CODE:
```
n = int(input("Enter the value of N: "))
total = 0

for i in range(2, n + 1, 2):
    total = total + i

print("Sum of even numbers =", total)

```

## OUTPUT:
Enter the value of N: 5
Sum of even numbers = 6

## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 7 - Reverse the digits of a number using a loop

## CODE:
```
num = int(input("Enter a number: "))
reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num = num // 10

print("Reversed number =", reverse)

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter a number: 451
Reversed number = 154
>>> 

## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 8 - Display a pattern using nested loops

## CODE:
```
n = int(input("Enter the number of rows: "))

for i in range(1, n + 1):
    for j in range(1, i + 1):
        print("*", end=" ")
    print()

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter the number of rows: 5
* 
* * 
* * * 
* * * * 
* * * * * 
>>> 

## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 9 -  Search for an element in an array using Linear Search

## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))
num = int(input("Enter element to search: "))

found = False

for i in range(len(arr)):
    if arr[i] == num:
        print("Element found at position", i + 1)
        found = True
        break

if not found:
    print("Element not found")

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter array elements: 4 5 3 21 6 7 5 4 
Enter element to search: 21
Element found at position 4
>>> 

## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 10 - Find the largest element in an array
## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))

largest = arr[0]

for i in arr:
    if i > largest:
        largest = i

print("Largest element =", largest)

```

## OUTPUT:
Enter array elements: 2 3 4 5 6 3 5 6 4 
Largest element = 6


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 11 - Find the smallest element in an array
## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))

smallest = arr[0]

for i in arr:
    if i < smallest:
        smallest = i

print("Smallest element =", smallest)

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter array elements: 4 5 6 0 8 2 
Smallest element = 0
>>> 


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 12 - Sort an array in ascending order using Bubble Sort

## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))

n = len(arr)

for i in range(n):
    for j in range(n - i - 1):
        if arr[j] > arr[j + 1]:
            arr[j], arr[j + 1] = arr[j + 1], arr[j]

print("Ascending order:", arr)

```

## OUTPUT:

>>> %Run -c $EDITOR_CONTENT
Enter array elements: 3 4 5 76 4 6 8 4 
Ascending order: [3, 4, 4, 4, 5, 6, 8, 76]
>>> 


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 13 - Sort an array in descending order
## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))

n = len(arr)

for i in range(n):
    for j in range(n - i - 1):
        if arr[j] < arr[j + 1]:
            arr[j], arr[j + 1] = arr[j + 1], arr[j]

print("Descending order:", arr)

```

## OUTPUT:

>>> %Run -c $EDITOR_CONTENT
Enter array elements: 1 2 4 6 4 8 7 56 43 67 23 09 56 00
Descending order: [67, 56, 56, 43, 23, 9, 8, 7, 6, 4, 4, 2, 1, 0]
>>> 


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 14 - Insert a new element at the end of an array

## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))
num = int(input("Enter element to insert: "))

arr.append(num)

print("Updated array:", arr)

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter array elements: 45 76 89 90 21 98
Enter element to insert: 30
Updated array: [45, 76, 89, 90, 21, 98, 30]
>>> 


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 15 - Insert a new element at a specified position in an array

## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))
num = int(input("Enter element to insert: "))
pos = int(input("Enter position: "))

if 1 <= pos <= len(arr) + 1:
    arr.insert(pos - 1, num)
    print("Updated array:", arr)
else:
    print("Invalid position")

```

## OUTPUT:
>>> %Run -c $EDITOR_CONTENT
Enter array elements: 23 45 54 65 78 12 34 56 76 
Enter element to insert: 75
Enter position: 2
Updated array: [23, 75, 45, 54, 65, 78, 12, 34, 56, 76]
>>> 


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 16 - Delete an element from a specified position in an array
## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))
pos = int(input("Enter position to delete: "))

if 1 <= pos <= len(arr):
    arr.pop(pos - 1)
    print("Updated array:", arr)
else:
    print("Invalid position")

```

## OUTPUT:

>>> %Run -c $EDITOR_CONTENT
Enter array elements: 22 3 56 32 17 30
Enter position to delete: 1
Updated array: [3, 56, 32, 17, 30]
>>>


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 17 -  Delete a given value from an array by searching for it
## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))
num = int(input("Enter value to delete: "))

if num in arr:
    arr.remove(num)
    print("Updated array:", arr)
else:
    print("Element not found")

```

## OUTPUT:

>>> %Run -c $EDITOR_CONTENT
Enter array elements: 3 4 6 1 8 5 4 2 
Enter value to delete: 4
Updated array: [3, 6, 1, 8, 5, 4, 2]
>>> 


## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:




## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:




## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:



## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 18 - 
## CODE:
```


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:
















