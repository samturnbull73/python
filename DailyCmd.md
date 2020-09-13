### DAY 1 

```
    1.Keywords
		2.Identifiers:- 
      variable name,Function name,class name
		  1.Alphabet(a-z|A-Z|0-9| _)
              abc123=10
      2.Digits should be not start
              123abc=10
      3.Python Keywords 
                if=10
      4.Case sensitive
                jaipur=10
                Jaipur=10
                a=10
                If=10
      5.no limit
                _temp=10
    3.Data type
          1. int a=32768;
                cout<<a;  -32768
		            1.Decimal Form  10    0to 9     56789
		            2.Binary Form   2     0 or 1    0b0101,0b101 0B101    bin()
		            3.Octal Form    8     0 to 7    0o5672 or 0O456       oct()
		            4.Hexdecimal Form 16  0 to 9    0x6789 or 0Xa         hex()
 				         10 a A
  				        11 b B
                  15 f F
                  print()
                  id()    
                  type()

          2.Float 123.456
          
          3.complex
             3+5j
          
          4.bool 		True or False

          5.str data type
            s1="Jaipur"
            'jaipur'
            '''jaipur'''
            '''This is "my" 'First' Job'''
```

### DAY 2

```
>>> s1='jaipur'
>>> s1[0]='m'
Traceback (most recent call last):
  File "<pyshell#1>", line 1, in <module>
    s1[0]='m'
TypeError: 'str' object does not support item assignment

>>> int(123.456)
123
>>> int(True)
1
>>> int(3+5j)

Traceback (most recent call last):
  File "<pyshell#4>", line 1, in <module>
    int(3+5j)
TypeError: can't convert complex to int
>>> int("matrix")
Traceback (most recent call last):
  File "<pyshell#5>", line 1, in <module>
    int("matrix")
ValueError: invalid literal for int() with base 10: 'matrix'
>>> int("10")
10
>>> int('0b101')
Traceback (most recent call last):
  File "<pyshell#7>", line 1, in <module>
    int('0b101')
ValueError: invalid literal for int() with base 10: '0b101'
>>> float(10)
10.0
>>> float(True)
1.0
>>> float(3+5j)
Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    float(3+5j)
TypeError: can't convert complex to float
>>> float("Jaipur")
Traceback (most recent call last):
  File "<pyshell#11>", line 1, in <module>
    float("Jaipur")
ValueError: could not convert string to float: 'Jaipur'
>>> float("10")
10.0
>>> float("0b101")
Traceback (most recent call last):
  File "<pyshell#13>", line 1, in <module>
    float("0b101")
ValueError: could not convert string to float: '0b101'
>>> float("123.456")
123.456
>>> complex(10)
(10+0j)
>>> complex(True)
(1+0j)
>>> complex(10.5)
(10.5+0j)
>>> complex("jaipur")
Traceback (most recent call last):
  File "<pyshell#18>", line 1, in <module>
    complex("jaipur")
ValueError: complex() arg is a malformed string
>>> complex("10")
(10+0j)
>>> complex("10.5")
(10.5+0j)
>>> complex(10,2)
(10+2j)
>>> complex(10,-2)
(10-2j)
>>> complex(True,False)
(1+0j)
>>> bool(10)
True
>>> bool(10.5)
True
>>> bool(0.178)
True
>>> bool(0.0)
False
>>> bool(3+5j)
True
>>> bool(0+5j)
True
>>> bool(0+0j)
False
>>> bool("jaipur")
True
>>> bool("")
False
>>> str(10)
'10'
>>> str("10.5")
'10.5'
>>> sstr(10+5j)
Traceback (most recent call last):
  File "<pyshell#35>", line 1, in <module>
    sstr(10+5j)
NameError: name 'sstr' is not defined
>>> str(10+5j)
'(10+5j)'
>>> str(True)
'True'
>>>    

>>> l1=[10,20,30,40]
>>> print(type(l1))
<class 'list'>
>>> b=bytes(l1)
>>> print(type(l1))
<class 'list'>
>>> print(type(b))
<class 'bytes'>
>>> l1=[10,20,30,256]
>>> b=bytes(l1)
Traceback (most recent call last):
  File "<pyshell#6>", line 1, in <module>
    b=bytes(l1)
ValueError: bytes must be in range(0, 256)
>>> l1=[10,20,30,40]
>>> b=bytes(l1)
>>> b[0]=100
Traceback (most recent call last):
  File "<pyshell#9>", line 1, in <module>
    b[0]=100
TypeError: 'bytes' object does not support item assignment
>>> l1=[10,20,30,40]
>>> b=bytearray(l1)
>>> print(type(b))
<class 'bytearray'>
>>> b[0]=100
>>> l1=[10,20,30,256]
>>> b=bytearray(l1)
Traceback (most recent call last):
  File "<pyshell#15>", line 1, in <module>
    b=bytearray(l1)
ValueError: byte must be in range(0, 256)
>>> l1=[10,103.45,True,3+5j,"Jaipur"]
>>> print(type(l1))
<class 'list'>
>>> print(l1)
[10, 103.45, True, (3+5j), 'Jaipur']
>>> l1[0]=100
>>> print(l1)
[100, 103.45, True, (3+5j), 'Jaipur']
>>> l1[0]
100
>>> t1=(10,20,30,40)
>>> print(type(t1))
<class 'tuple'>
>>> t1=(10,103.45,True,3+5j,"Jaipur")
>>> t1[0]=100
Traceback (most recent call last):
  File "<pyshell#25>", line 1, in <module>
    t1[0]=100
TypeError: 'tuple' object does not support item assignment
>>> range(10)
range(0, 10)
>>> for i in range(10):
  print(i)

  
0
1
2
3
4
5
6
7
8
9
>>> for i in range(10,20):
  print(i)

  
10
11
12
13
14
15
16
17
18
19
>>> for i in range(10,20,2):
  print(i)

  
10
12
14
16
18
>>>
```

### DAY 3
```
1.Arithmetic Operator
 + - * / %  // **
 floor division

2.Relational Operator 
 < <= > >=
 if condntion:
    statement
 else:
    statement

 if condition:
    if condition:


if condition:
   statement
elif condition:
   statement
elif...

else:


only if statement
if condition:
   statement
if condition:
  statement;

Equality Operator
 == !=

Logical Operator
 and or not

 and=if both argument are True then result is True
 or=if one argument are True then result is True
 not = complement

 0 menas False
 '' means False

 character input 
 alphabet Uppercase Lowercase
 digit 
 SP
 ch =a
 if a>b and  a>c
  print("uppercase") 
 ```
              
