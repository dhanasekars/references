
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
