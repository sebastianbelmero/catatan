### Variable dalam Python
```
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"
```

### Output
```
x = "awesome"
print("Python is " + x)
output = Python is awesome
```

### Global variable dan fungsi di Python
```
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()
# output : Python is fantastic
print("Python is " + x)
# output : Python is awesome
```

### Tipe data dalam Python
|Example|Data Type|
|--- |--- |
|x = "Hello World"|str|
|x = 20|int|
|x = 20.5|float|
|x = 1j|complex|
|x = ["apple", "banana", "cherry"]|list|
|x = ("apple", "banana", "cherry")|tuple|
|x = range(6)|range|
|x = {"name" : "John", "age" : 36}|dict|
|x = {"apple", "banana", "cherry"}|set|
|x = frozenset({"apple", "banana", "cherry"})|frozenset|
|x = True|bool|
|x = b"Hello"|bytes|
|x = bytearray(5)|bytearray|
|x = memoryview(bytes(5))|memoryview|

### Tipe data Spesifik
|Example|Data Type|
|--- |--- |
|x = str("Hello World")|str|
|x = int(20)|int|
|x = float(20.5)|float|
|x = complex(1j)|complex|
|x = list(("apple", "banana", "cherry"))|list|
|x = tuple(("apple", "banana", "cherry"))|tuple|
|x = range(6)|range|
|x = dict(name="John", age=36)|dict|
|x = set(("apple", "banana", "cherry"))|set|
|x = frozenset(("apple", "banana", "cherry"))|frozenset|
|x = bool(5)|bool|
|x = bytes(5)|bytes|
|x = bytearray(5)|bytearray|
|x = memoryview(bytes(5))|memoryview|