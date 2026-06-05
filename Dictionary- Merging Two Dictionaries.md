## Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program

```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

dict1.update(dict2)

print("Merged Dictionary:", dict1)
```

## Output
<img width="620" height="173" alt="image" src="https://github.com/user-attachments/assets/afc194a8-999e-4036-93bb-1b61ac86d024" />

## Result
Thus, the Python program to merge two dictionaries and combine their key-value pairs was executed successfully, and the merged dictionary was obtained.
