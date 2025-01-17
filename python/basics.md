# basics

## ways to define a string

- single quotes
  - `s = 'hello'`
- double quotes
  - `s = "hello"`
- triple quotes
  - `s = '''hello'''`

## string concatenation

```py
s1 = 'hello'
s2 = 'world'
s3 = s1 + ' ' + s2
print(s3)
```

## string slicing

```py
s = 'hello world'
print(s[2,5,2])
```

## string methods

you can refer to documentation for this section it have isalnum isalpha isdigit islower isupper istitle isspace etc. etc. bs thingys no one uses (I mean not much)

## string formatting

```py
name = 'John'
age = 25
print('My name is {} and I am {} years old'.format(name, age))
```

```py
print(f'My name is {name} and I am {age} years old')
```

## Integers & floats

(khud se)

## List

### defining a list

```py
a= [1,2,3,4,5]
```

### blank list

```py
a= [ ]
a= list()
```

### list indexing

```py
a= [1,2,3,4,5]
print(a[2])
```

## List Methods

```py
a= [1,2,3,4,5]
a.append(6)
print(a)
```

```py
a.remove(3) # removes the first occurence of 3
```

```py
a.pop() # removes the last element
a.pop(2) # removes the element at index 2
```

```py
a.insert(2, 7) # inserts 7 at index 2
```

```py
a.extend([8,9,10]) # appends the list [8,9,10] to a
```

## Dictionary

```py
a= {1: 'one', 2: 'two', 3: 'three'}
print(a[1])
```

### Dictionary Methods

```py
a= {1: 'one', 2: 'two', 3: 'three'}
a[4]= 'four'
print(a)
```

```py
print(a.keys())
print(a.values())
print(a.items())
```

```py
a.pop(2)
```

```py
a.update({4: 'four', 5: 'five'})
```

## Sets

- Not much used tbh but still they only store unique values and are unordered so faster than lists
- Since it have same curly braces as dictionary so you have to use set() to define a blank set

```py
a = {1,2,3,4,5,5,5,5,5}
print(a)
```

## Tuples

- Immutable bande

```py
a= (1,2,4)
```
