# Python-Tutorial
### Python Syntax
print("Hello, Would!")
### Python Indentation
if 6 > 4:
  print("Six is greater than four!")
### Python Variables
x = 5
y = "Hello, World!"
### Python Comments
#This is a comment.
print("Hello, Wonju!")
print("Hello, Wonju!") #This is a comment
#print("Hello, Wonju!")
print("Goodluck, Friend!")
### Python Multiline Comments
#This is a comment
#written in
#more than just one line
print("Hello, Busan!")
"""
This is a comment
written in
more than just one line
"""
print("Hello, Busan!")
### Python Variables
x = 5
y = "SHIN"
print(x)
print(y)

x = 4       # x is of type int
x = "Sally" # x is now of type str
print(x)
### Casting
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
### Get the Type
x = 5
y = "John"
print(type(x))
print(type(y))
### Single or Double Quotes?
x = "SHIN"
# is the same as
x = 'SHIN'
### Case-Sensitive
a = 19
A = "Min Sung"
#A will not overwrite a
### Python - Variable Names
myvar = "SHIN"
my_var = "SHIN"
_my_var = "SHIN"
myVar = "SHIN"
MYVAR = "SHIN"
myvar2 = "SHIN"
## Multi Words Variable Names
### Camel Case
myVariableName = "SHIN"
### Pascal Case
MyVariableName = "SHIN"
### Snake Case
my_variable_name = "SHIN"
## Python Variables - Assign Multiple Values
### Many Values to Multiple Variables
x, y, z = "Moka", "Milk", "Coffee"
print(x)
print(y)
print(z)
### One Value to Multiple Variables
x = y = z = "Moka"
print(x)
print(y)
print(z)
### Unpack a Collection
fruits = ["Moka", "Milk", "Coffee"]
x, y, z = fruits
print(x)
print(y)
print(z)
## Python - Output Variables
### Output Variables
x = "Python is unbelievable"
print(x)

x = "Python"
y = "is"
z = "unbelievable"
print(x, y, z)

x = "Python "
y = "is "
z = "unbelievable"
print(x + y + z)

x = 5
y = "SHIN"
print(x, y)
### Python - Global Variables
## Global Variables
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()

x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
## The global Keyword
def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)

x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
### Python Data Types
## Getting the Data Type
x = 5
print(type(x))
### Python Numbers
x = 1    # int
y = 2.8  # float
z = 1j   # complex

print(type(x))
print(type(y))
print(type(z))
## Int
x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))
## Float
x = 1.10
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))

x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))
## Complex
x = 3+5j
y = 5j
z = -5j

print(type(x))
print(type(y))
print(type(z))
## Type Conversion
x = 1    # int
y = 2.8  # float
z = 1j   # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
## Random Number
import random

print(random.randrange(1, 10))
### Python Casting
## Specify a Variable Type
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3

x = float(1)     # x will be 1.0
y = float(2.8)   # y will be 2.8
z = float("3")   # z will be 3.0
w = float("4.2") # w will be 4.2

x = str("s1") # x will be 's1'
y = str(2)    # y will be '2'
z = str(3.0)  # z will be '3.0'
### Python Strings
## Strings
print("Hello")
print('Hello')
## Assign String to a Variable
a = "Hello"
print(a)
## Multiline Strings
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)

a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''
print(a)
### Python - Slicing Strings
## Slicing
b = "Hello, World!"
print(b[2:5])
## Slice From the Start
b = "Hello, World!"
print(b[:5])
## Slice To the End
b = "Hello, World!"
print(b[2:])
## Negative Indexing
b = "Hello, World!"
print(b[-5:-2])
### Python - Modify Strings
## Upper Case
a = "Hello, World!"
print(a.upper())
## Lower Case
a = "Hello, World!"
print(a.lower())
## Remove Whitespace
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
## Replace String
a = "Hello, World!"
print(a.replace("H", "J"))
## Split String
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
### Python - String Concatenation
## String Concatenation
a = "Hello"
b = "World"
c = a + b
print(c)

a = "Hello"
b = "World"
c = a + " " + b
print(c)
### Python - Format - Strings
## String Format
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))

quantity = 3
itemno = 567
price = 49.95
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price))

quantity = 3
itemno = 567
price = 49.95
myorder = "I want to pay {2} dollars for {0} pieces of item {1}."
print(myorder.format(quantity, itemno, price))
### Python - Escape Characters
## Escape Character
txt = "We are the so-called \"Vikings\" from the north."
### Python Booleans
## Boolean Values
print(10 > 9)
print(10 == 9)
print(10 < 9)

a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
## Evaluate Values and Variables
print(bool("Hello"))
print(bool(15))

x = "Hello"
y = 15

print(bool(x))
print(bool(y))
## Most Values are True
bool("abc")
bool(123)
bool(["apple", "cherry", "banana"])
## Some Values are False
bool(False)
bool(None)
bool(0)
bool("")
bool(())
bool([])
bool({})

class myclass():
  def __len__(self):
    return 0

myobj = myclass()
print(bool(myobj))
## Functions can Return a Boolean
def myFunction() :
  return True

print(myFunction())

def myFunction() :
  return True

if myFunction():
  print("YES!")
else:
  print("NO!")

x = 200
print(isinstance(x, int))
### Python Operators
## Python Operators
print(10 + 5)
## Operator Precedence
print((6 + 3) - (6 + 3))
print(100 + 5 * 3)
print(5 + 4 - 7 + 3)
### Python Lists
## List
thislist = ["apple", "banana", "cherry"]
print(thislist)
## Allow Duplicates
thislist = ["apple", "banana", "cherry", "apple", "cherry"]
print(thislist)
## List Length
thislist = ["apple", "banana", "cherry"]
print(len(thislist))
## List Items - Data Types
list1 = ["apple", "banana", "cherry"]
list2 = [1, 5, 7, 9, 3]
list3 = [True, False, False]

list1 = ["abc", 34, True, 40, "male"]
## type()
mylist = ["apple", "banana", "cherry"]
print(type(mylist))
## The list() Constructor
thislist = list(("apple", "banana", "cherry")) # note the double round-brackets
print(thislist)
### Python - Access List Items
## Access Items
thislist = ["apple", "banana", "cherry"]
print(thislist[1])
## Negative Indexing
thislist = ["apple", "banana", "cherry"]
print(thislist[-1])
## Range of Indexes
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:5])
### Python - Change List Items
## Change Item Value
thislist = ["apple", "banana", "cherry"]
thislist[1] = "blackcurrant"
print(thislist)
## Change a Range of Item Values
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]
thislist[1:3] = ["blackcurrant", "watermelon"]
print(thislist)

thislist = ["apple", "banana", "cherry"]
thislist[1:2] = ["blackcurrant", "watermelon"]
print(thislist)

thislist = ["apple", "banana", "cherry"]
thislist[1:3] = ["watermelon"]
print(thislist)
## Insert Items
thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "watermelon")
print(thislist)
### Python - Add List Items
## Append Items
thislist = ["apple", "banana", "cherry"]
thislist.append("orange")
print(thislist)
## Insert Items
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)
## Extend List
thislist = ["apple", "banana", "cherry"]
tropical = ["mango", "pineapple", "papaya"]
thislist.extend(tropical)
print(thislist)
## Add Any Iterable
thislist = ["apple", "banana", "cherry"]
thistuple = ("kiwi", "orange")
thislist.extend(thistuple)
print(thislist)
### Python - Remove List Items
## Remove Specified Item
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)

thislist = ["apple", "banana", "cherry", "banana", "kiwi"]
thislist.remove("banana")
print(thislist)
## Remove Specified Index
thislist = ["apple", "banana", "cherry"]
thislist.pop(1)
print(thislist)

thislist = ["apple", "banana", "cherry"]
thislist.pop()
print(thislist)

thislist = ["apple", "banana", "cherry"]
del thislist[0]
print(thislist)

thislist = ["apple", "banana", "cherry"]
del thislist
## Clear the List
thislist = ["apple", "banana", "cherry"]
thislist.clear()
print(thislist)
### Python - Loop Lists
## Loop Through a List
thislist = ["apple", "banana", "cherry"]
for x in thislist:
  print(x)
## Loop Through the Index Numbers
thislist = ["apple", "banana", "cherry"]
for i in range(len(thislist)):
  print(thislist[i])
## Using a While Loop
thislist = ["apple", "banana", "cherry"]
i = 0
while i < len(thislist):
  print(thislist[i])
  i = i + 1
## Looping Using List Comprehension
thislist = ["apple", "banana", "cherry"]
[print(x) for x in thislist]
### Python - List Comprehension
## List Comprehension
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "a" in x:
    newlist.append(x)

print(newlist)
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "a" in x]

print(newlist)
## Condition
newlist = [x for x in fruits if x != "apple"]

newlist = [x for x in fruits]
## Iterable
newlist = [x for x in range(10)]

newlist = [x for x in range(10) if x < 5]
## Expression
newlist = [x.upper() for x in fruits]

newlist = ['hello' for x in fruits]

newlist = [x if x != "banana" else "orange" for x in fruits]
### Python - Sort Lists
## Sort List Alphanumerically
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort()
print(thislist)

thislist = [100, 50, 65, 82, 23]
thislist.sort()
print(thislist)
## Sort Descending
thislist = ["orange", "mango", "kiwi", "pineapple", "banana"]
thislist.sort(reverse = True)
print(thislist)

thislist = [100, 50, 65, 82, 23]
thislist.sort(reverse = True)
print(thislist)
## Customize Sort Function
def myfunc(n):
  return abs(n - 50)

thislist = [100, 50, 65, 82, 23]
thislist.sort(key = myfunc)
print(thislist)
## Case Insensitive Sort
thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.sort()
print(thislist)

thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.sort(key = str.lower)
print(thislist)
## Reverse Order
thislist = ["banana", "Orange", "Kiwi", "cherry"]
thislist.reverse()
print(thislist)
### Python - Copy Lists
## Copy a List
thislist = ["apple", "banana", "cherry"]
mylist = thislist.copy()
print(mylist)

thislist = ["apple", "banana", "cherry"]
mylist = list(thislist)
print(mylist)\
### Python - Join Lists
## Join Two Lists
list1 = ["a", "b", "c"]
list2 = [1, 2, 3]

list3 = list1 + list2
print(list3)

list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

for x in list2:
  list1.append(x)

print(list1)

list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list1.extend(list2)
print(list1)
### Python Tuples
## Tuple
thistuple = ("apple", "banana", "cherry")
print(thistuple)
## Allow Duplicates
thistuple = ("apple", "banana", "cherry", "apple", "cherry")
print(thistuple)
## Tuple Length
thistuple = ("apple", "banana", "cherry")
print(len(thistuple))
## Create Tuple With One Item
thistuple = ("apple",)
print(type(thistuple))

#NOT a tuple
thistuple = ("apple")
print(type(thistuple))
## Tuple Items - Data Types
tuple1 = ("apple", "banana", "cherry")
tuple2 = (1, 5, 7, 9, 3)
tuple3 = (True, False, False)

tuple1 = ("abc", 34, True, 40, "male")
mytuple = ("apple", "banana", "cherry")
## type() 
mytuple = ("apple", "banana", "cherry")
print(type(mytuple))
## The tuple() Constructor
thistuple = tuple(("apple", "banana", "cherry")) # note the double round-brackets
print(thistuple)
### Python - Access Tuple Items
## Access Tuple Items
thistuple = ("apple", "banana", "cherry")
print(thistuple[1])
## Negative Indexing
thistuple = ("apple", "banana", "cherry")
print(thistuple[-1])
## Range of Indexes
thistuple = ("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
print(thistuple[2:5])

thistuple = ("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
print(thistuple[:4])

thistuple = ("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
print(thistuple[2:])
## Range of Negative Indexes
thistuple = ("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
print(thistuple[-4:-1])
## Check if Item Exists
thistuple = ("apple", "banana", "cherry")
if "apple" in thistuple:
  print("Yes, 'apple' is in the fruits tuple")
### Python - Update Tuples
## Change Tuple Values
x = ("apple", "banana", "cherry")
y = list(x)
y[1] = "kiwi"
x = tuple(y)

print(x)
## Add Items
thistuple = ("apple", "banana", "cherry")
y = list(thistuple)
y.append("orange")
thistuple = tuple(y)

thistuple = ("apple", "banana", "cherry")
y = ("orange",)
thistuple += y

print(thistuple)
### Python - Unpack Tuples
## Unpacking a Tuple
fruits = ("apple", "banana", "cherry")
fruits = ("apple", "banana", "cherry")

(green, yellow, red) = fruits

print(green)
print(yellow)
print(red)
## Using Asterisk
fruits = ("apple", "banana", "cherry", "strawberry", "raspberry")

(green, yellow, *red) = fruits

print(green)
print(yellow)
print(red)

fruits = ("apple", "mango", "papaya", "pineapple", "cherry")

(green, *tropic, red) = fruits

print(green)
print(tropic)
print(red)
### Python - Loop Tuples
## Loop Through a Tuple
thistuple = ("apple", "banana", "cherry")
for x in thistuple:
  print(x)
## Loop Through the Index Numbers
thistuple = ("apple", "banana", "cherry")
for i in range(len(thistuple)):
  print(thistuple[i])
## Using a While Loop
thistuple = ("apple", "banana", "cherry")
i = 0
while i < len(thistuple):
  print(thistuple[i])
  i = i + 1
### Python - Join Tuples
## Join Two Tuples
tuple1 = ("a", "b" , "c")
tuple2 = (1, 2, 3)

tuple3 = tuple1 + tuple2
print(tuple3)
## Multiply Tuples
fruits = ("apple", "banana", "cherry")
mytuple = fruits * 2

print(mytuple)
### Python Sets
## Set
thisset = {"apple", "banana", "cherry"}
print(thisset)
## Duplicates Not Allowed
thisset = {"apple", "banana", "cherry", "apple"}

print(thisset)

thisset = {"apple", "banana", "cherry", True, 1, 2}

print(thisset)

thisset = {"apple", "banana", "cherry", False, True, 0}

print(thisset)
### Python - Access Set Items
## Access Items
thisset = {"apple", "banana", "cherry"}

for x in thisset:
  print(x)

thisset = {"apple", "banana", "cherry"}

print("banana" in thisset)
### Python - Add Set Items
## Add Items
thisset = {"apple", "banana", "cherry"}

thisset.add("orange")

print(thisset)
## Add Sets
thisset = {"apple", "banana", "cherry"}
tropical = {"pineapple", "mango", "papaya"}

thisset.update(tropical)

print(thisset)
## Add Any Iterable
thisset = {"apple", "banana", "cherry"}
mylist = ["kiwi", "orange"]

thisset.update(mylist)

print(thisset)
### Python - Remove Set Items
## Remove Item
thisset = {"apple", "banana", "cherry"}

thisset.remove("banana")

print(thisset)

thisset = {"apple", "banana", "cherry"}

thisset.discard("banana")

print(thisset)

thisset = {"apple", "banana", "cherry"}

x = thisset.pop()

print(x)

print(thisset)

thisset = {"apple", "banana", "cherry"}

thisset.clear()

print(thisset)

thisset = {"apple", "banana", "cherry"}

del thisset

print(thisset)
### Python - Loop Sets
## Loop Items
thisset = {"apple", "banana", "cherry"}

for x in thisset:
  print(x)
### Python - Join Sets
## Join Two Sets
set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}

set3 = set1.union(set2)
print(set3)

set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}

set1.update(set2)
print(set1)
## Keep ONLY the Duplicates
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

x.intersection_update(y)

print(x)

x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.intersection(y)

print(z)
## Keep All, But NOT the Duplicates
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

x.symmetric_difference_update(y)

print(x)

x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.symmetric_difference(y)

print(z)

x = {"apple", "banana", "cherry", True}
y = {"google", 1, "apple", 2}

z = x.symmetric_difference(y)

print(z)
### Python Dictionaries
## Dictionary
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
## Dictionary Items
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict["brand"])
## Duplicates Not Allowed
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964,
  "year": 2020
}
print(thisdict)
## Dictionary Length
print(len(thisdict))
## Dictionary Items - Data Types
thisdict = {
  "brand": "Ford",
  "electric": False,
  "year": 1964,
  "colors": ["red", "white", "blue"]
}
## type()
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(type(thisdict))
## The dict() Constructor
thisdict = dict(name = "John", age = 36, country = "Norway")
print(thisdict)
### Python - Access Dictionary Items
## Accessing Items
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict["model"]

x = thisdict.get("model")
## Get Keys
x = thisdict.keys()

car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.keys()

print(x) #before the change

car["color"] = "white"

print(x) #after the change
## Get Values
x = thisdict.values()

car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.values()

print(x) #before the change

car["year"] = 2020

print(x) #after the change

car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.values()

print(x) #before the change

car["color"] = "red"

print(x) #after the change
## Get Items
x = thisdict.items()

car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.items()

print(x) #before the change

car["year"] = 2020

print(x) #after the change
car = {
"brand": "Ford",
"model": "Mustang",
"year": 1964
}

x = car.items()

print(x) #before the change

car["color"] = "red"

print(x) #after the change
## Check if Key Exists
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
if "model" in thisdict:
  print("Yes, 'model' is one of the keys in the thisdict dictionary")
### Python - Change Dictionary Items
## Change Values
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict["year"] = 2018
## Update Dictionary
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.update({"year": 2020})
### Python - Add Dictionary Items
## Adding Items
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict["color"] = "red"
print(thisdict)
## Update Dictionary
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.update({"color": "red"})
### Python - Remove Dictionary Items
## Removing Items
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.pop("model")
print(thisdict)

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.popitem()
print(thisdict)

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
del thisdict["model"]
print(thisdict)

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.clear()
print(thisdict)
### Python - Loop Dictionaries
## Loop Through a Dictionary
for x in thisdict:
  print(x)

for x in thisdict:
  print(thisdict[x])

for x in thisdict.values():
  print(x)

for x in thisdict.keys():
  print(x)

for x, y in thisdict.items():
  print(x, y)
### Python - Copy Dictionaries
## Copy a Dictionary
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
mydict = thisdict.copy()
print(mydict)

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
mydict = dict(thisdict)
print(mydict)
### Python - Nested Dictionaries
## Nested Dictionaries
myfamily = {
  "child1" : {
    "name" : "Emil",
    "year" : 2004
  },
  "child2" : {
    "name" : "Tobias",
    "year" : 2007
  },
  "child3" : {
    "name" : "Linus",
    "year" : 2011
  }
}

child1 = {
  "name" : "Emil",
  "year" : 2004
}
child2 = {
  "name" : "Tobias",
  "year" : 2007
}
child3 = {
  "name" : "Linus",
  "year" : 2011
}

myfamily = {
  "child1" : child1,
  "child2" : child2,
  "child3" : child3
}
## Access Items in Nested Dictionaries
print(myfamily["child2"]["name"])
### Python If ... Else
## Python Conditions and If statements
a = 33
b = 200
if b > a:
  print("b is greater than a")
## Elif
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
## Else
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")

a = 200
b = 33
if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
## Short Hand If
if a > b: print("a is greater than b")
## Short Hand If ... Else
a = 2
b = 330
print("A") if a > b else print("B")

a = 330
b = 330
print("A") if a > b else print("=") if a == b else print("B")

## And
a = 200
b = 33
c = 500
if a > b and c > a:
  print("Both conditions are True")
## Or
a = 200
b = 33
c = 500
if a > b or a > c:
  print("At least one of the conditions is True")
## Not
a = 33
b = 200
if not a > b:
  print("a is NOT greater than b")
## Nested If
x = 41

if x > 10:
  print("Above ten,")
  if x > 20:
    print("and also above 20!")
  else:
    print("but not above 20.")
## The pass Statement
a = 33
b = 200

if b > a:
  pass
### Python While Loops
## The while Loop
i = 1
while i < 6:
  print(i)
  i += 1
## The break Statement
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1
## The continue Statement
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
## The else Statement
i = 1
while i < 6:
  print(i)
  i += 1
else:
  print("i is no longer less than 6")
### Python For Loops
## Python For Loops
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
## Looping Through a String
for x in "banana":
  print(x)
## The break Statement
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break

fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    break
  print(x)
## The continue Statement
  fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
## The range() Function
for x in range(6):
  print(x)
for x in range(2, 6):
  print(x)
for x in range(2, 30, 3):
  print(x)
## Else in For Loop
for x in range(6):
  print(x)
else:
  print("Finally finished!")
for x in range(6):
  if x == 3: break
  print(x)
else:
  print("Finally finished!")
## Nested Loops
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)
## The pass Statement
for x in [0, 1, 2]:
  pass














