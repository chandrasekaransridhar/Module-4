# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```py
try:
    l=[1,2,3,4]
    c=l[5]
    print(c)
except Exception:
    print("You're out of list range.")
```
## Output
<img width="1241" height="182" alt="image" src="https://github.com/user-attachments/assets/f8c9473f-bb51-4823-92ab-3656299fe3a2" />


## Result
successfully wrote Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

