![banner](https://user-images.githubusercontent.com/55238388/111981947-5f62d080-8b2e-11eb-98a8-e463fddf7a23.jpg)

<h1 align="center">Python Basics - Week 1 - Day 2</h1>

## Short Hand If

If you have only one statement to execute, you can put it on the same line as the if statement.

```
if a > b: print("a is greater than b")
```

## Short Hand If ... Else

If you have only one statement to execute, one for if, and one for else, you can put it all on the same line:

```
a = 2
b = 330
print("A") if a > b else print("B")
```

One line if else statement, with 3 conditions:

```
a = 330
b = 330
print("A") if a > b else print("=") if a == b else print("B")
```

## And

The ```and``` keyword is a logical operator, and is used to combine conditional statements:

```
a = 200
b = 33
c = 500
if a > b and c > a:
  print("Both conditions are True")
```

```NOTE : In Python, AND operator has higher precedence than OR operator. So, it is evaluated first```

## Or

The ```or``` keyword is a logical operator, and is used to combine conditional statements:

```
a = 200
b = 33
c = 500
if a > b or a > c:
  print("At least one of the conditions is True")
```
## Not

The ```not``` keyword is a logical operator.
The return value will be ```True``` if the statement(s) are not ```True```, otherwise it will return ```False``.

```
x = False

print(not x)
```

```NOTE : In Python the precedence order is first NOT then AND and in last OR ```


## Nested If

You can have ```if``` statements inside ```if``` statements, this is called ```nested if``` statements.

```
x = 41

if x > 10:
  print("Above ten,")
  if x > 20:
    print("and also above 20!")
  else:
    print("but not above 20.")
```

## The pass Statement


```if``` statements cannot be empty, but if you for some reason have an ```if``` statement with no content, put in the ```pass``` statement to avoid getting an error.

```
a = 33
b = 200

if b > a:
  pass
```

## Recap and exercise