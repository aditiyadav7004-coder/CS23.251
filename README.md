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



## Assignment 18 - Bellman-Ford Algorithm
## CODE:
```
def bellman_ford(graph, vertices, edges, source):
    distance = [float('inf')] * vertices
    distance[source] = 0

    for i in range(vertices - 1):
        for u, v, w in edges:
            if distance[u] != float('inf') and distance[u] + w < distance[v]:
                distance[v] = distance[u] + w

    for u, v, w in edges:
        if distance[u] != float('inf') and distance[u] + w < distance[v]:
            print("Negative weight cycle detected")
            return

    print("Vertex\tDistance from Source")
    for i in range(vertices):
        print(i, "\t", distance[i])


vertices = int(input("Enter number of vertices: "))
e = int(input("Enter number of edges: "))
edges = []

for i in range(e):
    u, v, w = map(int, input("Enter source, destination and weight: ").split())
    edges.append((u, v, w))

source = int(input("Enter source vertex: "))
bellman_ford(None, vertices, edges, source)


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 19 - Dijkstra's Algorithm
## CODE:
```
import heapq

def dijkstra(graph, source):
    distance = {vertex: float('inf') for vertex in graph}
    distance[source] = 0
    pq = [(0, source)]

    while pq:
        dist, vertex = heapq.heappop(pq)

        if dist > distance[vertex]:
            continue

        for neighbour, weight in graph[vertex]:
            new_dist = dist + weight

            if new_dist < distance[neighbour]:
                distance[neighbour] = new_dist
                heapq.heappush(pq, (new_dist, neighbour))

    print("Vertex\tDistance from Source")
    for vertex in graph:
        print(vertex, "\t", distance[vertex])


graph = {}
n = int(input("Enter number of vertices: "))

for i in range(n):
    graph[i] = []

e = int(input("Enter number of edges: "))

for i in range(e):
    u, v, w = map(int, input("Enter source, destination and weight: ").split())
    graph[u].append((v, w))
    graph[v].append((u, w))

source = int(input("Enter source vertex: "))
dijkstra(graph, source)


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 20 - Depth First Search (DFS)
## CODE:
```
graph = {
    'A': ['B', 'C'],
    'B': ['A', 'D', 'E'],
    'C': ['A', 'F'],
    'D': ['B'],
    'E': ['B'],
    'F': ['C']
}

def dfs(graph, start, visited=None):
    if visited is None:
        visited = set()

    visited.add(start)
    print(start, end=" ")

    for neighbour in graph[start]:
        if neighbour not in visited:
            dfs(graph, neighbour, visited)

dfs(graph, 'A')


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 21 - Breadth First Search (BFS)
## CODE:
```
from collections import deque

graph = {
    'A': ['B', 'C'],
    'B': ['A', 'D', 'E'],
    'C': ['A', 'F'],
    'D': ['B'],
    'E': ['B'],
    'F': ['C']
}

def bfs(graph, start):
    visited = set()
    queue = deque([start])
    visited.add(start)

    while queue:
        vertex = queue.popleft()
        print(vertex, end=" ")

        for neighbour in graph[vertex]:
            if neighbour not in visited:
                visited.add(neighbour)
                queue.append(neighbour)

bfs(graph, 'A')


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 22 - Graph Creation Using User Input
## CODE:
```
graph = {}

n = int(input("Enter number of vertices: "))
m = int(input("Enter number of edges: "))

for i in range(n):
    vertex = input("Enter vertex: ")
    graph[vertex] = []

for i in range(m):
    u, v = input("Enter edge (u v): ").split()
    graph[u].append(v)
    graph[v].append(u)

print("Graph representation:")

for vertex in graph:
    print(vertex, ":", graph[vertex])


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 23 - Represent Given Directed Graphs
## CODE:
```
graph = {
    'A': ['B', 'C'],
    'B': ['D'],
    'C': ['D'],
    'D': []
}

for vertex in graph:
    print(vertex, "->", graph[vertex])


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 24 - Graph Representation Using Classes and Objects
## CODE:
```
class Graph:
    def __init__(self):
        self.graph = {}

    def add_edge(self, u, v):
        if u not in self.graph:
            self.graph[u] = []
        if v not in self.graph:
            self.graph[v] = []
        self.graph[u].append(v)
        self.graph[v].append(u)

    def display(self):
        for vertex in self.graph:
            print(vertex, ":", self.graph[vertex])

g = Graph()

g.add_edge(0, 1)
g.add_edge(0, 2)
g.add_edge(1, 3)
g.add_edge(2, 3)

g.display()


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:


## Assignment 25 - Fibonacci Series Using Recursion
## CODE:
```
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

n = int(input("Enter number of terms: "))

if n <= 0:
    print("Enter a positive number")
else:
    for i in range(n):
        print(fibonacci(i), end=" ")


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 26 - Sum of Numbers Using Recursion
## CODE:
```
def sum_numbers(n):
    if n == 0:
        return 0
    return n + sum_numbers(n - 1)

n = int(input("Enter a number: "))

if n < 0:
    print("Enter a non-negative number")
else:
    print("Sum:", sum_numbers(n))


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 27 - Factorial Using Recursion
## CODE:
```
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

n = int(input("Enter a number: "))

if n < 0:
    print("Factorial is not defined for negative numbers")
else:
    print("Factorial:", factorial(n))


```

## OUTPUT:



## ALGORITHM:
```python

```

## FLOWCHART:

## Assignment 28 - Delete Element by Value in Array
## CODE:
```
arr = list(map(int, input("Enter array elements: ").split()))
value = int(input("Enter value to delete: "))

if value in arr:
    arr.remove(value)
    print("Array after deletion:", arr)
else:
    print("Element not found")


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
















