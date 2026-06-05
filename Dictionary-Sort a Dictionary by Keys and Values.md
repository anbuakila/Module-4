# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

##  Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

print("Keys in alphabetical order:")
for key in sorted(d.keys()):
    print(key)

print("Values in alphabetical order:")
for value in sorted(d.values()):
    print(value)
```
## Sample Output
<img width="446" height="412" alt="image" src="https://github.com/user-attachments/assets/c4b279a2-af02-44eb-abe2-e2a931d6ccde" />

## Result
Thus, the Python program to sort a dictionary's keys and values in alphabetical order was executed successfully, and the sorted keys and values were displayed.
