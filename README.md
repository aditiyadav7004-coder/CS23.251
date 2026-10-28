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

<img width="412" height="265" alt="image" src="https://github.com/user-attachments/assets/26433478-9ac3-41c4-bfe1-849de811850a" />


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

<img width="373" height="240" alt="image" src="https://github.com/user-attachments/assets/b0fb314b-00ad-4a31-a1ef-ac2535238dd3" />


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

<img width="425" height="202" alt="image" src="https://github.com/user-attachments/assets/f67e210e-4ec1-4f10-811f-c0a54a5ba7e8" />


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

<img width="380" height="353" alt="image" src="https://github.com/user-attachments/assets/5c823618-d4fd-4966-b9de-e9603c262f1e" />


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

<img width="283" height="413" alt="image" src="https://github.com/user-attachments/assets/89e14a67-958b-4255-872e-2cb3b2150224" />



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

<img width="471" height="186" alt="image" src="https://github.com/user-attachments/assets/a8c246ff-f015-446b-93e5-41d1e5efe1c8" />



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

<img width="450" height="202" alt="image" src="https://github.com/user-attachments/assets/18dd193e-a79f-4198-a0c1-d1e7debeeaf4" />

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

<img width="423" height="326" alt="image" src="https://github.com/user-attachments/assets/50a24d5a-d8ea-46b2-887e-f38e96f421ef" />


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

<img width="515" height="227" alt="image" src="https://github.com/user-attachments/assets/b8dd1c1b-4ea5-4d96-8406-5f4f49452897" />

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

<img width="565" height="206" alt="image" src="https://github.com/user-attachments/assets/738db4c1-4cfe-447c-bcd1-e03882527b23" />


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

<img width="716" height="207" alt="image" src="https://github.com/user-attachments/assets/f37998da-7117-4896-99cc-ffe7ebb52ff7" />


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

<img width="623" height="187" alt="image" src="https://github.com/user-attachments/assets/f529c329-b83a-4d28-bd12-31441504a537" />



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

<img width="590" height="187" alt="image" src="https://github.com/user-attachments/assets/a17e647e-0ddf-4903-ba8b-88dda7de0f82" />



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

<img width="682" height="196" alt="image" src="https://github.com/user-attachments/assets/437e444f-0e32-404b-aceb-61ed1e6fe7f1" />



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

<img width="772" height="282" alt="image" src="https://github.com/user-attachments/assets/a6761d67-3bf1-4f59-8b41-15b879c36a48" />



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

<img width="610" height="227" alt="image" src="https://github.com/user-attachments/assets/0a968370-4c05-407e-8009-8385c1a37341" />



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

<img width="537" height="205" alt="image" src="https://github.com/user-attachments/assets/7464560c-e845-44dd-87ec-103238e4ddd1" />



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

<img width="517" height="397" alt="image" src="https://github.com/user-attachments/assets/695bd9fc-5a8b-4d05-bb7a-3f24184f39de" />



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

<img width="696" height="363" alt="image" src="https://github.com/user-attachments/assets/48809ead-4fa9-4581-b536-0af984516e96" />


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

<img width="218" height="145" alt="image" src="https://github.com/user-attachments/assets/e7d8db08-d29b-4034-9fd0-e63669c9fed7" />



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

<img width="200" height="197" alt="image" src="https://github.com/user-attachments/assets/b43ebfdb-3fd8-4524-af03-11c92a33d68e" />



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

<img width="455" height="527" alt="image" src="https://github.com/user-attachments/assets/b0ce5098-740d-4f78-b304-405763e44aac" />



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

<img width="282" height="197" alt="image" src="https://github.com/user-attachments/assets/c3ccca8b-ee57-418f-afc0-59a1a5b73550" />


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

<img width="331" height="225" alt="image" src="https://github.com/user-attachments/assets/b39cf88c-ebd2-4ea6-8b48-39209cf39281" />


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

<img width="380" height="182" alt="image" src="https://github.com/user-attachments/assets/33579b94-003e-48cb-82e5-7e90c89c8c1e" />


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

<img width="325" height="180" alt="image" src="https://github.com/user-attachments/assets/d7e59e93-08f3-43eb-bccf-1525ecda91ac" />



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

<img width="350" height="167" alt="image" src="https://github.com/user-attachments/assets/099067c4-9c48-4c4b-974e-83a12ed1ae89" />



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

<img width="665" height="217" alt="image" src="https://github.com/user-attachments/assets/3bd3ea3c-bf02-4768-8cee-9d11128a0dbe" />



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
















