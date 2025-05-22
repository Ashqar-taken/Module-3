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
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if(re.search(r'e',i)):
        pass
    else:
        l1.append(i)

print(l1)
```
## Output

![Screenshot 2025-05-22 112508](https://github.com/user-attachments/assets/18f40cbe-e809-4bba-a273-dc523a49fe27)

## Result
A Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expression (regex)** was written successfully.
