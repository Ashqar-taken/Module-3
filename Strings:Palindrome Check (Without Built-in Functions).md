# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
str = input("Enter a string: ")
str2 = ""
str2 = str[::-1]
if(str2 == str):
    print("The given string is a palindrome")
else:
    print("The given string is not a plaindrome")
```
## Output

![Screenshot 2025-05-22 114431](https://github.com/user-attachments/assets/ca1be00a-c08f-41e3-9875-9e7fc6066948)


## Result
A Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions was written successfully.
