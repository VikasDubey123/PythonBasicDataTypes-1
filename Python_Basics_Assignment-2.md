```python
# 1.What are the two values of the Boolean data type? How do you write them?
# Ans: True and False which corresponds to 1 and 0.

```


```python
# 2. What are the three different types of Boolean operators?
# Ans: The three types of boolean operators are AND, OR and NOT.

```


```python
# 3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate).
# Ans: AND Table:
#   A	B	Output
#   F	F	F
#   F	T	F
#   T	F	F
#   T	T	T

# OR Table:
#   A	B	Output
#   F	F	F
#   F	T	T
#   T	F	T
#   T	T	T

# AND Table:
#   A	Output
#   F	T
#   T	F

```


```python
# 4. What are the values of the following expressions?
# (5 > 4) and (3 == 5)
# Ans: False
# not (5 > 4)
# Ans: False
# (5 > 4) or (3 == 5)
# Ans: True
# not ((5 > 4) or (3 == 5))
# Ans: False
# (True and True) and (True == False)
# Ans: False
# (not False) or (not True)
# Ans: True

```


```python
# 5. What are the six comparison operators?
# Ans: Less than ( < ), Less than or equal to ( <= ), Greater than ( > ), Greater than or equal to ( >= ), 
#      Equal to ( == ) and Not equal to ( != ) are six comparison operators.
```


```python
# 6. How do you tell the difference between the equal to and assignment operators? Describe a condition and when you would use one.
# Ans: Equal to operator is used to check the contain of a variable while assignment operator is used to assign a value to a variable. 
# Example: if we want to check whether a number is even or odd then it can be done by checking the remainder of divide by 2 is equal to 0 or not by equal to operator and if it is even then counter can be increased by one using assignment operator.

```


```python
# 7. Identify the three blocks in this code:
# spam = 0
# if spam == 10:
#     print('eggs')
#     if spam > 5:
#         print('bacon')
#     else:
#         print('ham')
#     print('spam')
# print('spam')
# Ans: The three blocks are everything inside the if statement and the lines print('bacon') and print('ham').

```


```python
# 8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, 
# and prints Greetings! if anything else is stored in spam.
spam = input("Give an input: ")
if spam == '1':
    print('Hello')
elif spam == '2':
    print('Howdy')
else:
     print('Greetings')   
```

    Give an input: er
    Greetings
    


```python
# 9.If your programme is stuck in an endless loop, what keys you’ll press?
# Ans: CLTR + C
```


```python
# 10. How can you tell the difference between break and continue?
# Ans: Break statement breaks the loop inside which it is written while continue statement runs the loop even no operation 
#      is happening inside the loop.
```


```python
# 11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?
# Ans: In for loop there is no difference between range(10), range(0, 10) and range(0, 10, 1) becouse all will start from 0 go
#      to 10-1 i.e. 9 with the step size of 1.
```


```python
# 12. Write a short program that prints the numbers 1 to 10 using a for loop. 
# Then write an equivalent program that prints the numbers 1 to 10 using a while loop.

# Using for loop
for i in range(1,11):
    print(i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
# Using while loop
i = 1
while i <= 10:
    print(i)
    i+=1
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
# 13. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?
# Ans: from spam import bacon
```
