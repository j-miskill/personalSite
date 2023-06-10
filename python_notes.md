# Python Notes

## Range

When using the range function (which is used a lot in for loops), it is not inclusive. The second number in the range is not included in the range.

```
range(0,5)
# 0,1,2,3,4 but not 5
```

Important to remember for algorithms.

## Sets

Python has something called sets, which are data structures that are essentially hashmaps within Python.

They have super quick lookup times.

## Lambda expressions

Need a function but only one time? No reason to write one out for yourself. You can use lambda functions in Python (which was something I learned about in my SDE class in Fall 2022).

```
expression = lambda y: print("This is lambda")
print(expression())
```

This is super neat.
