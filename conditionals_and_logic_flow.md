## Conditionals, Logic Flow and Comments

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

## In
The in keyword, when used with a conditional, tells you whether some text appears in a string.

```python
if 'Messica Arson' in article:
  print('It is so awesome Jess got her DJ project in this article')
```

## And  
Using the and keyword, both conditions must be true for the print statement to run.

```python
if homework_turned_in == 0 and homework_assigned == 1:
  print('Jess is sad')
```

## Or
Using the or keyword, either condition could be true for the print statement to run.
```python
if state == 'MD' or state == 'DC' or state == 'DE' or state == 'VA' or state == 'PA':
  print('You are from the Mid-Atlantic region')
```

## Nested Conditionals
```python
if state == 'NY':
  print('You are in NY')
elif state == 'NJ':
  print('You are in NJ')
elif state == ('CT')
  print('')
else:
  print('We only service the New York Region')

  if state == 'PA':
    print('You are welcome to visit us still')
  elif state == 'CA':
    print('Wow, that would be quite the drive')
```

## Comments
Comments are code that doesn't run.

```python
# I am a comment, I don't run
print('hello world!')
```
