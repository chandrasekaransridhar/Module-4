## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```py
dic1={1:"muruga",2:"vel",3:"kantha",4:"palni"}
dic2={5:"vetri",6:"arupadai"}
def merge():
    meg={**dic1,**dic2}
    return meg
c=merge()
print(c)
```

## Output
<img width="1600" height="283" alt="image" src="https://github.com/user-attachments/assets/4657e98f-8938-4325-9d1f-5ab9a964ef13" />

## Result
successfully wrote Python program that merges **two dictionaries** and combines their key-value pairs.
