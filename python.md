To find python path in mac OS X

```
which python
```


## variable names

* always small letters
* Upper case has a special purpose, avoid in varialble names
* underscore_allowed
* use meaningful name



## Errors in python

### Name Error

```
print(a * b)
```

```
Traceback (most recent call last):
  File "3day.py", line 1, in <module>
    print(a * b)
NameError: name 'a' is not defined
```


### Type Error

```
print("Print this " + 20)
```
```
Traceback (most recent call last):
  File "3day.py", line 1, in <module>
    print("Hourly wage: " + 20)
TypeError: can only concatenate str (not "int") to str
```

example 2

```
duplicate = [{'count': 1},]
print(type(duplicate))

for i in duplicate:
    print(duplicate[i])
```

Reference : https://stackoverflow.com/questions/26266425/typeerror-list-indices-must-be-integers-not-dict

```
duplicate = [{'count': 1},]
print(type(duplicate))

for i in duplicate:
    print(i['count'])
```


### Index Error

```
details = [ "name", 37, "Director"]
print(details[3])
```
```
Traceback (most recent call last):
  File "4day.py", line 2, in <module>
    print(details[3])
IndexError: list index out of range
```
