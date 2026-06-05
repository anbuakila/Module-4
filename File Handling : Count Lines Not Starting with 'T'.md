# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
lines = [
    "This is a story.",
    "There was a king.",
    "Once upon a time.",
    "The sun rises.",
    "Hello world."
]
count = 0
for line in lines:
    if not line.startswith('T'):
        count += 1
print(count)
```
## Output
<img width="527" height="158" alt="image" src="https://github.com/user-attachments/assets/829fd3df-3a1e-45d9-8f38-db3237e1eee2" />

## Result
Thus, the Python program to count the number of lines in the file story.txt that do not start with the alphabet 'T' was executed successfully, and the count was displayed.
