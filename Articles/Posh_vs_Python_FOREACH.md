
In Python, the equivalent of `foreach($obj in $objects) {}` is a `for` loop. Here's an example:

```powershell
# PowerShell foreach loop
$objects = @("apple", "banana", "orange")
foreach($obj in $objects) {
    Write-Host $obj
}
```

```python
# Python for loop
objects = ["apple", "banana", "orange"]
for obj in objects:
    print(obj)
```

This will output the following:

```
apple
banana
orange
```

In Python, the `for` loop iterates over a sequence, such as a list, tuple, or string. The loop variable (`obj` in this case) is assigned the value of each element in the sequence, one at a time, until the sequence is exhausted.

Here are a few more examples:

1. Using `range()` function to iterate over a sequence of numbers:

```python
# Iterate over a sequence of numbers
for i in range(5):
    print(i)
```

This will output the following:

```
0
1
2
3
4
```

2. Using `enumerate()` function to iterate over a sequence and its index:

```python
# Iterate over a sequence and its index
fruits = ["apple", "banana", "orange"]
for i, fruit in enumerate(fruits):
    print(i, fruit)
```

This will output the following:

```
0 apple
1 banana
2 orange
```

In this example, `enumerate()` function is used to iterate over both the index and the value of each element in the `fruits` list.

3. Using `zip()` function to iterate over multiple sequences in parallel:

```python
# Iterate over multiple sequences in parallel
fruits = ["apple", "banana", "orange"]
colors = ["red", "yellow", "orange"]
for fruit, color in zip(fruits, colors):
    print(fruit, color)
```

This will output the following:

```
apple red
banana yellow
orange orange
```

In this example, `zip()` function is used to iterate over both the `fruits` and `colors` lists in parallel, matching up their corresponding elements.
