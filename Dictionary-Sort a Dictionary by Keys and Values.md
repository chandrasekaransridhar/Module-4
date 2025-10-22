# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

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
```py
l={'apple':2,'banana':1,'orange':3,'watermelon':5}
c=dict(sorted(l.items()))
k=dict(sorted(l.items(),key=lambda item:item[1]))
print(c)
print(k)
```


## Sample Output
<img width="1508" height="176" alt="image" src="https://github.com/user-attachments/assets/343b1f39-9d25-48f0-b9e2-473669f4dcc6" />


## Result
successfully wrote Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

