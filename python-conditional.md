## Conditional Statements

### If, Else If, Else

If, Else If, and Else are conditional statements, meaning that the condition set by the statement decides which statement will be executed.

The format is usually as follows:

```python
if (condition1):
	# code to be executed
elif (condition2):
	# different code to be executed
# more elifs if needed
else:
	# another different set of code to be executed
```

For example:

```python
for x in range(0,5):
	if (x == 0):
		print("hello")
	elif (x == 1 or x == 2):
		print("second or third")
	elif (x == 3):
		print("4")
	else:
		print("last value left to check")
```

Would print:

```python
hello
second or third
second or third
4
last value left to check
```

Notice how all the terms aren't just printed 5 times each as in the example in the For-Loops section.

We can also test if things are *not* true (false). Let's say we want to print out all grades that were not passing grades:
```py
grades = [55, 98, 78, 79, 35]
for each in grades:
	if not each > 65:
		print "AP Classes are hard, man"
```
We are saying, if a value is NOT this, do the following.
