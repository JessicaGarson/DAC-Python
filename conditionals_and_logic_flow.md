## Conditionals 

## Operators for Comparison
```
==   These two things are equal
!=	 NOT! equal to
>	   Greater than
<	   Less than
>=   Greater than or equal to
<=   Less than or equal to
```

```python
1 == 2
2 != 3
5 > 4
3 < 100
4 >= 92
4 <= 5
```

## Conditionals
Conditionals are very similar to flow charts. They change our code based on behavior.

## If Statement
The if statement evaluates whether a statement is true or false, and run code only in the case that the statement is true.

```python
space = 15
if space < 20:
  print('We still have spaces left')
```

## Else
If none of the conditions meet. Than do this.

```python
space = 21

if space < 20:
  print('We still have spaces left')
else:
  print('Sorry, we are full')
```

## Elif
If there is another condition that is met than do something else.

```
if condition:
    do something
elif other_condition:
    do something else
else:
    do another thing
```

```python
space = 19
if space < 20:
  print('We still have space left')
elif space == 20:
  print('We are just a capacity')
elif space >= 15:
  print('We are almost at capacity but we have a few spaces left')
else:
  print('Sorry, we are full')
```
