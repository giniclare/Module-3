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
s = "google"

rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```

## Output
<img width="437" height="123" alt="image" src="https://github.com/user-attachments/assets/0e986f2e-e242-4bf0-8d9e-8c1c14869d85" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome was successfully executed, and it was found that the string is not a palindrome.

