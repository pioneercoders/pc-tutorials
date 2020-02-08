<h4> Loops </h4>

In programming, a **loop** means repeating something multiple times.

<h4>For loop</h4>
    
```python
# Program to find the sum of all numbers stored in a list

# List of numbers
numbers = [6, 5, 3, 8, 4, 2, 5, 4, 11]

# variable to store the sum
sum = 0

# iterate over the list
for val in numbers:
	sum = sum+val

# Output: The sum is 48
print("The sum is", sum)
```
<h4>The range() </h4>

```python
print(range(10))
# Output: range(0, 10)

print(list(range(10)))
# Output: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

print(list(range(2, 8)))
# Output: [2, 3, 4, 5, 6, 7]

print(list(range(2, 20, 3)))
# Output: [2, 5, 8, 11, 14, 17]
```

<h4> print the integer 2 through 10 using a "for" loop </h4>
```python
for i in range(2, 11):
    print(i)
```

<h4> While loops </h4>

While loops are really similar to if statements.

```python
# print the integer 2 through 10 using a "while" loop
i = 2
while i < 11:
    print(i)
    i = i + 1
 ```
 
