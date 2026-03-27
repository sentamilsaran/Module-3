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

## 🧾 Program:
```
# Program to check palindrome string

s = "google"

# Reverse string
rev = s[::-1]

# Check palindrome
if s == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```

## Output:

<img width="535" height="241" alt="image" src="https://github.com/user-attachments/assets/5e078214-e43a-4bcc-a9c3-5d4e51dae080" />

## Result:

Thus, the Python program to check whether a string is a palindrome without using built-in functions was successfully executed and verified.
