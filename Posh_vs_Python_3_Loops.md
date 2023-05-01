[Return to Main Article](/Articles/Posh_vs_Python.md)<br>

# Loops

PowerShell and Python both support loops, including for and while loops. However, the syntax for these loops is different. In PowerShell, a for loop uses the syntax "for ($i = 0; $i -lt 10; $i++) {do something}", while in Python it uses the syntax "for i in range(10): do something". Similarly, a while loop in PowerShell uses the syntax "while (condition) {do something}", while in Python it uses "while condition: do something".

Here are some more in-depth examples of loops in PowerShell and Python:

1. For Loops:

In PowerShell, you can use a for loop to iterate over a range of values. Here's an example:

```
for ($i=1; $i -le 5; $i++) {
    Write-Host $i
}
```

This will output:

```
1
2
3
4
5
```

In Python, you can use a for loop to iterate over a sequence of values. Here's an example:

```
for i in range(1, 6):
    print(i)
```

This will output:

```
1
2
3
4
5
```

2. While Loops:

In PowerShell, you can use a while loop to execute code while a condition is true. Here's an example:

```
$i = 1
while ($i -le 5) {
    Write-Host $i
    $i++
}
```

This will output:

```
1
2
3
4
5
```

In Python, you can use a while loop to execute code while a condition is true. Here's an example:

```
i = 1
while i <= 5:
    print(i)
    i += 1
```

This will output:

```
1
2
3
4
5
```

3. Nested Loops:

In PowerShell, you can use nested loops to iterate over multiple sequences. Here's an example:

```
for ($i=1; $i -le 3; $i++) {
    for ($j=1; $j -le 3; $j++) {
        Write-Host "$i,$j"
    }
}
```

This will output:

```
1,1
1,2
1,3
2,1
2,2
2,3
3,1
3,2
3,3
```

In Python, you can use nested loops to iterate over multiple sequences. Here's an example:

```
for i in range(1, 4):
    for j in range(1, 4):
        print(f"{i},{j}")
```

This will output:

```
1,1
1,2
1,3
2,1
2,2
2,3
3,1
3,2
3,3
```

Note that in Python, f-strings are used to format the output, which is a more concise and readable way of formatting strings compared to concatenation or other methods.


[Return to Main Article](/Articles/Posh_vs_Python.md)<br>
