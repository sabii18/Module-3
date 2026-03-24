# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

~~~
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search("e", i):
        l1.append(i)

print(l1)
~~~


## Output

<img width="658" height="355" alt="image" src="https://github.com/user-attachments/assets/19730593-4308-4a79-9796-be7fa7acc4d7" />


## Result

The Python program to filter words that do not contain the letter 'e' using regular expressions was executed successfully and the output was verified.
