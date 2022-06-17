1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.
* ----- Expression
'hello'  ----- Values
-87.8  ------- Values
-    ------- Expression
/    ------- Expression
+	 ------- Expression
6    ------- Values

Ans: Values are: 'hello', -87.8, 6
     Expression are: * -, /, +

2. What is the difference between string and variable?
Ans: String is a type of datatype(information) which is stored in a variable, while variable is a container which stores or contains any type of information like string, integer, float or double, list etc...

3. Describe three different data types.
Ans: Three different data types are: 
    1) Numeric: It is a datatype which holds numbers of type int, float or complex type.
    2) Boolean: It is a datatype which holds boolean values such as 1(True) or 0(False).
    3) Dictionary: It is a datatype which holds values in a pair of Key and values. Values can be same but keys should be different.
    4) Set: It a datatype which holds unique values only.

4. What is an expression made up of? What do all expressions do?
Ans: An expression consists of operators and operand which are interpreted to produce another value. 
    eg. 2*3 = 6, so 2 & 3 are operands and * is operator and 2*3 is an expression.

5. This assignment statements, like spam = 10. What is the difference between an expression and a statement?
Ans: An assignment statement like, spam = 10 assigns value of 10 to variable spam but an expression produces new value which is result of the operation performed on operands by operator during expression interpretation. 

```python
# 6. After running the following code, what does the variable bacon contain?
bacon = 22
bacon + 1
```
    23
Ans : The value of variable bacon contain = 23


```python
# 7. What should the values of the following two terms be?
'spam' + 'spamspam'
```

    'spamspamspam'

```python
'spam' * 3
```

    'spamspamspam'

Ans: The values of the following two terms will be same as 'spamspamspam' i.e. spam 3 times.

8. Why is eggs a valid variable name while 100 is invalid?

Ans: Variable names in python should never starts with numbers and special characters, if we want to use numbers then variable name should begin with letter then number like eggs100 is valid variable name. 

9. What three functions can be used to get the integer, floating-point number, or string version of a value?

Ans: int(), float() and str().

10. Why does this expression cause an error? How can you fix it?
'I have eaten ' + 99 + ' burritos.'

Ans:  We trying to add two different data types such as string with integer as 99 is integer, hence we get an error. To fix this this problem we have to change the data types by using typecasting.
