[Return to Main Article](/Articles/Posh_vs_Python.md)<br>

# Conditional Statements

PowerShell and Python both support conditional statements such as if-else statements, but their syntax is slightly different. In PowerShell, the syntax for an if statement is `if (condition) {do something}`, while in Python it's `if condition: do something`. Both languages also support else-if statements, but the syntax differs slightly.

## 1. If Statements:

In PowerShell, you can use an if statement to test a condition and execute code if the condition is true. Here's an example:

```
$age = 30
if ($age -gt 18) {
    Write-Host "You are an adult"
}
```

In Python, you can use an if statement to test a condition and execute code if the condition is true. Here's an example:

```
age = 30
if age > 18:
    print("You are an adult")
```

## 2. If-Else Statements:

In PowerShell, you can use an if-else statement to test a condition and execute code if the condition is true, and a different code if it is false. Here's an example:

```
$age = 16
if ($age -gt 18) {
    Write-Host "You are an adult"
}
else {
    Write-Host "You are a minor"
}
```

In Python, you can use an if-else statement to test a condition and execute code if the condition is true, and a different code if it is false. Here's an example:

```
age = 16
if age > 18:
    print("You are an adult")
else:
    print("You are a minor")
```
## 3. Switch-Case Statements:

In PowerShell, to check multiple conditions, use a switch statement. The switch statement is equivalent to a series of if statements, but it is simpler. The switch statement lists each condition and an optional action. If a condition obtains, the action is performed. More Details: [about_Switch](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_switch?view=powershell-7.3)

```
$num = 3
switch ($num)
{
    1 {"It is one."}
    2 {"It is two."}
    3 {"It is three."}
    4 {"It is four."}
    Default {"No Match"}
}
```
Output 
```
It is three.
```

From version 3.10 upwards, Python has implemented a switch case feature called “structural pattern matching”. You can implement this feature with the match and case keywords.

```
num = input("Input a number between 1 and 4")

match num:
    case 1:
        print("It is one.")
    case 2:
        print("It is two.")
    case 3:
        print("It is three.")
    case 4:
        print("It is four.")
    case _:
        print("No Match.")
```

[Return to Main Article](/Articles/Posh_vs_Python.md)<br>